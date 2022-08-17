<script context="module">
  export const prerender = true;
</script>

<script>
import SideNavExample from "$lib/content/SideNavExample.svelte";



 
</script>

<svelte:head>
  <title>Grid: Demo of some of the ways to layout rows</title>
</svelte:head>


<div class="mainContent">
  <div class="row"><SideNavExample /></div>
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
