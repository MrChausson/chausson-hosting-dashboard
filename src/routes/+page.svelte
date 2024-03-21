<script>
	//import Counter from './Counter.svelte';
    import BeamMPdashboard from './BeamMPdashboard.svelte';
</script>

<svelte:head>
	<title>Your Dashboard</title>
	<meta name="Chausson Hosting Dashboard" content="Svelte demo app" />
</svelte:head>

<section>
	<BeamMPdashboard />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

</style>
