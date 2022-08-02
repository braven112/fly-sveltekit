<script context="module">
  export const prerender = true;
</script>

<script>
import DefaultFormElements from "$lib/content/DefaultFormElements.svelte"; 
</script>

<svelte:head>
  <title>Grid: Demo of some of the ways to layout rows</title>
</svelte:head>


<div class="mainContent">
  <div class="row"><DefaultFormElements /></div>
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
