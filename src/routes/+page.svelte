<svelte:head>
	<title>APKStore</title>
	<meta name="description" content="APKStore" />
</svelte:head>

<script lang="ts">
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcomeFallback from '$lib/images/svelte-welcome.png';
	import Button, { Label } from '@smui/button';
    import Card, { Content } from '@smui/card';
</script>

<section>
	<h1>Welcome to APKStore!</h1>
</section>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 24</Content>
</Card>
<Card style="width: 100%; margin: 2em auto;">
    <Content>
        <div class="element">
            <img src="https://raw.githubusercontent.com/errortek/jpb24/refs/heads/master/app/src/main/res/mipmap-xxxhdpi/ic_launcher.webp" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>jpb24 1.0</h4>
            <p>by jpb</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<style>
	h1 {
		width: 100%;
	}
	.element {
	    margin: 10px;
	    float: left;
	}
	img {
      display: block;
      margin-left: auto;
      margin-right: auto;
      width: 40%;
    }
</style>
