<script context="module">
  export const prerender = true;
</script>

<script>
  import GridAutoCol from "$lib/content/GridAutoCol.svelte";
  import GridFourCol from "$lib/content/GridFourCol.svelte";
  import GridThreeCol from "$lib/content/GridThreeCol.svelte";
import GridTwoCol from "$lib/content/GridTwoCol.svelte";
 
</script>

<svelte:head>
  <title>Grid: Demo of some of the ways to layout rows</title>
</svelte:head>


<div class="mainContent">
  <auro-header margin="bottom" size="none">Auro Grid</auro-header>
  <p>Simplify your UX on tablet and mobile</p>
  <div class="row"><GridTwoCol /></div>
  <div class="row"><GridThreeCol /></div>
  <div class="row"><GridFourCol /></div>
  <div class="row"><GridAutoCol /></div>
</div>

<style>
	.mainContent {
    padding: var(--padding);
    display: block;
}
.row {
  margin-bottom: 3rem;
}

</style>
