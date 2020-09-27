<script>
	
</script>

<svelte:head>
	<title>Sapper SASS Template</title>
</svelte:head>

<section>
	<h1>A Sapper Sass Template</h1>
	<p>Configured with global and variables sass files</p>
</section>

<style type="text/scss">
	@import './styles/variables';

	section {
		margin-top: 10rem;

		& h1 {
			color: $main-color;
		}
	}

	
	
</style>