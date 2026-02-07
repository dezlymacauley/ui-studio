<script lang="ts">
  import "$lib/css/global.css";
  import faviconSvg from "$lib/svg/svelte_logo.svg";
  let { children } = $props();
</script>

<svelte:head>
  <link rel="icon" href={faviconSvg}>
</svelte:head>

{@render children()}
