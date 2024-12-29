<svelte:head>
	<title>APKStore</title>
	<meta name="description" content="APKStore" />
</svelte:head>

<script lang="ts">
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcomeFallback from '$lib/images/svelte-welcome.png';
	import Button from '@smui/button';
    import Card, { Content } from '@smui/card';
</script>

<section>
	<h1>Welcome to APKStore!</h1>
</section>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 24</Content>
</Card>

<style>

	h1 {
		width: 100%;
	}
</style>
