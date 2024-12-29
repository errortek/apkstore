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
  <Content class="mdc-typography--body2">December 29</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://raw.githubusercontent.com/Surge-OS/surge-dl-components/refs/heads/master/catalog/java/io/material/catalog/ic_launcher-playstore.png" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>SurgeOS Design Language Catalog 1.2</h4>
            <p>by jpb</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">December 28</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://raw.githubusercontent.com/Surge-OS/surge-dl-components/refs/heads/master/catalog/java/io/material/catalog/ic_launcher-playstore.png" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>SurgeOS Design Language Catalog 1.0</h4>
            <p>by jpb</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">December 26</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://raw.githubusercontent.com/errortek/jpb24/refs/heads/master/app/src/main/res/mipmap-xxxhdpi/ic_launcher.webp" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>jpb24 1.1</h4>
            <p>by jpb</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">November 20</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
        </div>
        <div class="element">
            <h4>Music 1.1</h4>
            <p>by jpb</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">November 7</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
        </div>
        <div class="element">
            <h4>Music 1.0</h4>
            <p>by jpb</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 24</Content>
</Card>
<Card style="width: 100%;">
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

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 4</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://raw.githubusercontent.com/errortek/notes/refs/heads/main/app/src/main/ic_launcher-playstore.png" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>Notes 2.0</h4>
            <p>by jpb</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">September 26</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://raw.githubusercontent.com/errortek/notes/refs/heads/main/app/src/main/ic_launcher-playstore.png" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>Notes 1.5.5</h4>
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
    }
</style>
