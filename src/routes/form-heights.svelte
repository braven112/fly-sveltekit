<script context="module">
  export const prerender = true;
</script>

<script>
import FormHeight from "$lib/content/FormExamples.svelte"; 
</script>

<svelte:head>
  <title>Forms Height: Validate our form elements</title>
</svelte:head>


<div class="mainContent">
  <div class="row"><FormHeight /></div>
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
