<script>
  import BelgiumExplorer from '$lib/BelgiumExplorer.svelte';

  let { data } = $props();
</script>

<svelte:head>
  <title>Carte des communes — CCAPV</title>
  <meta name="description" content="Explorer la grille des communes de la CCAPV." />
</svelte:head>

<BelgiumExplorer geojson={data.geojson} />
