<script lang="ts">
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcomeFallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>APKStore</title>
	<meta name="description" content="APKStore" />
</svelte:head>

<section>
	<h1>Welcome to APKStore!</h1>
</section>

<style>

	h1 {
		width: 100%;
	}
</style>
