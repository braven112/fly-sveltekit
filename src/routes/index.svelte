<script context="module">
  export const prerender = true;
</script>

<script>
  import Enrollment from "$lib/content/Enrollment.svelte";
  import Hero from "$lib/content/Hero.svelte"
  import UpcomingTrips from "$lib/content/UpcomingTrips.svelte";
  import WatchList from "$lib/content/WatchList.svelte";
</script>

<svelte:head>
  <title>Fly: Employee Travel</title>
</svelte:head>

	<Hero />
<div class="mainContent">
  <Enrollment />
  <UpcomingTrips />
  <WatchList />
</div>

<style>
	.mainContent {
    padding: var(--padding);
}

</style>
