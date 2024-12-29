<script lang="ts">
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcomeFallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>APKStore</title>
	<meta name="description" content="APKStore" />

  <!-- Fonts -->
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/icon?family=Material+Icons"
  />
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,600,700"
  />

  <!-- Material Typography -->
  <link
    rel="stylesheet"
    href="https://unpkg.com/@material/typography@14.0.0/dist/mdc.typography.css"
  />

  <!-- SMUI -->
  <link rel="stylesheet" href="https://unpkg.com/svelte-material-ui/bare.css" />
</svelte:head>

<section>
	<h1>Welcome to APKStore!</h1>
</section>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 24</Content>
</Card>

<script>
  import Button from '@smui/button';
  import Card, { Content } from '@smui/card';
</script>

<style>

	h1 {
		width: 100%;
	}
</style>
