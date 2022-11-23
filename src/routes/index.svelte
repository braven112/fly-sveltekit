<script context="module">
  export const prerender = true;
</script>

<script>
  import BreadcrumbExample from "$lib/content/BreadcrumbExample.svelte";
import Enrollment from "$lib/content/Enrollment.svelte";
    import FormExamples from "$lib/content/FormExamples.svelte";
    import GridAutoCol from "$lib/content/GridAutoCol.svelte";
    import HeroSimple from "$lib/content/HeroSimple.svelte";
  import UpcomingTrips from "$lib/content/UpcomingTrips.svelte";
  import WatchList from "$lib/content/WatchList.svelte";
</script>

<svelte:head>
  <title>Fly: Employee Travel</title>
</svelte:head>
<div class="mainContent">
  <BreadcrumbExample />
  </div>
	<HeroSimple />
<div class="mainContent">
  <GridAutoCol />
  <Enrollment />
  <UpcomingTrips />
  <WatchList />
  <FormExamples />
</div>

<style>
	.mainContent {
    padding: var(--padding);
}

</style>
