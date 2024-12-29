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
            <Button onclick={() => window.location.href = "https://apkstore.vercel.app/apps/surgedl-catalog/1.2"}>
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

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">September 4</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.5.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">December 4, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.4.4</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">December 3, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.4.3</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">August 5, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.4.2</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">August 1, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.4.1</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">June 1, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.4.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">March 30, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.9</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">March 5, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.8</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">March 1, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.7</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">January 31, 2023</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.6</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">December 13, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.5</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">November 5, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.4</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">November 1, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.3</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">September 14, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.2</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.1</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">August 22, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.3.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">July 15, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.11</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">June 18, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.10</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">June 10, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.9</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">May 30, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.8</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">May 27, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.7</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">May 14, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.6</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">May 7, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.5</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">April 24, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.4</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">April 10, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.3</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">March 23, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.2</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">January 21, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.1</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">January 8, 2022</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.2.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">December 25, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.14</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">December 12, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.13</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">November 14, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.11</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 23, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.10</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 7, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.9</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">October 1, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.8</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">August 27, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.7</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">August 1, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.4</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">July 25, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.3</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">July 11, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.1</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">July 10, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.1.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">June 20, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.0.14</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">May 20, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.0.13</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">May 9, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.0.12</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">March 27, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.0.9</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">February 12, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.0.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">February 6, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.0.0-beta03</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
            <p><b>PRERELEASE</b></p>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">February 1, 2021</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 2.0.0-beta01</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
            <p><b>PRERELEASE</b></p>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">November 27, 2020</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 1.10.5</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">November 16, 2020</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 1.10.3</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">September 27, 2020</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 1.9.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">September 2, 2020</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 1.8.0</h4>
            <p>by zhaobozhen</p>
        </div>
        <div style="float: right;">
            <Button>
                <Label>Download</Label>
            </Button>
        </div>
    </Content>
</Card>

<Card style="width: 100%; margin: 2em auto;">
  <Content class="mdc-typography--body2">May 20, 2020</Content>
</Card>
<Card style="width: 100%;">
    <Content>
        <div class="element">
            <img src="https://github.com/LibChecker/LibChecker/blob/master/app/src/main/ic_launcher-playstore.png?raw=true" height="64" width="64"/>
        </div>
        <div class="element">
            <h4>LibChecker 1.3.2</h4>
            <p>by zhaobozhen</p>
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
