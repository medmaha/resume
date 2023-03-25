<script>
	// import Counter from './Counter.svelte';
	import Resume from "./Resume.svelte";
</script>

<svelte:head>
	<title>Mahamed Toure | Resume</title>
	<meta name="description" content="Mahamed Toure's personal resume" />
</svelte:head>

<section>
	<Resume />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
</style>
