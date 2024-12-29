<svelte:head>
	<title>SurgeOS Design Catalog 1.2 - APKStore</title>
	<meta name="description" content="Download SurgeOS Design Catalog" />
</svelte:head>

<Card style="width: 100%;">
    <Content>
        <div>
          <!--
            Note: tabs must be unique. (They cannot === each other.)
          -->
          <TabBar tabs={['Package information', "What's New", 'Description']} bind:active>
            {#snippet tab(tab)}
              <!-- Note: the `tab` property is required! -->
              <Tab {tab}>
                <Label>{tab}</Label>
              </Tab>
            {/snippet}
          </TabBar>

          {#if active === 'Package Information'}
            <Paper role="tabpanel" variant="unelevated">
              <Content>
              <div class="element">
                <p>Package Name:</p>
                <p>App size:</p>
                <p>Target API:</p>
                <p>Min API:</p>
              </div>
              <div class="element">
                <p>io.material.catalog</p>
                <p>16.10 MB</p>
                <p>Android 13 (API 33)</p>
                <p>Android 5.0 Lollipop (API 21)</p>
              </div>
              <div style="float: right;">
                          <Button>
                              <Label>Download</Label>
                          </Button>
                      </div>
              </Content>
            </Paper>
          {:else if active === "What's New"}
            <Paper role="tabpanel" variant="unelevated">
              <Content>What's New
                       Update target SDK and compile SDK to 35 (d9ee5ca)
                       Remove active indicator from bottom navigation bar (86a9d9f)
                       Remove active indicator from navigation rail (66f43eb)
                       Revert FloatingActionButton shape to circular (8f366e1)
                       Remove bottom border from TabView (1405e40)
                       Fix bottom sheet and side sheet crashes (027c864)
                       Known issues
                       Some dialogs (time and date picker) still have larger corner radii</Content>
            </Paper>
          {:else if active === 'Description'}
            <Paper role="tabpanel" variant="unelevated">
              <Content>Modern and easily customizable UI components, used in SurgeOS System Apps</Content>
            </Paper>
          {/if}

          <div style="margin-top: 1em;">
            <div>Programmatically select:</div>
            {#each ['Home', 'Merchandise', 'About Us'] as tab}
              <Button onclick={() => (active = tab)}><Label>{tab}</Label></Button>
            {/each}
          </div>
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
<script lang="ts">
  import Tab, { Label } from '@smui/tab';
  import TabBar from '@smui/tab-bar';
  import Button from '@smui/button';
  import Paper, { Content } from '@smui/paper';

  let active = $state('Home');
</script>
