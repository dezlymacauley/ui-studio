<script lang="ts">
  import favicon from "$lib/assets/svelte_logo.svg";
  import "./page.css";
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<style>
  @reference "./page.css";

  .brand-heading {

    /* Apply a left → right background gradient to the element box */
    @apply bg-linear-to-r from-purple-500 to-fuchsia-700;

    /* The text must be large and bold enough for you to see the effects */
    @apply text-lg font-extrabold;

    /* 
      Make the inner color of the text transparent.
    */
    @apply text-transparent;

    /*
      This will ensure that the background gradient color only appears,
      inside the letters of the text, 
      instead of appearing across the entire h1.
    */
    @apply bg-clip-text;
  }

</style>

<div class="">
  <h1 class="brand-heading">Dezly Macauley</h1>
</div>
