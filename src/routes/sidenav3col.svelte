<script context="module">
  export const prerender = true;
</script>

<script>
    import SideNav3ColExample from "$lib/content/SideNav3ColExample.svelte";




 
</script>

<svelte:head>
  <title>Sidenav: Demo of a fixed side nav and a fluid right hand column</title>
</svelte:head>


<div class="mainContent">
  <div class="row"><SideNav3ColExample /></div>
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
