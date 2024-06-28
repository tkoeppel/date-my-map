<script>
import { GradientButton } from 'flowbite-svelte';
</script>


<svelte:head>
	<title>Home</title>
	<meta name="description" content="Date My Map app" />
</svelte:head>

<section>
	<h1>Find out the creation date of your map</h1>
	
	<GradientButton color="redToYellow">
		<a href="/date">Start Dating</a>
	</GradientButton>
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
		margin-bottom: 1em;
	}
</style>
