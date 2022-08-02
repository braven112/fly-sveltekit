<script context="module">
  export const prerender = true;
</script>

<script>
import DefaultFormElements from "$lib/content/DefaultFormElements.svelte"; 
</script>

<svelte:head>
  <title>Forms: All of our auro form elements on one page</title>
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
