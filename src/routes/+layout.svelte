<script>
  import "../app.css";

  import Hero from "../lib/components/Hero.svelte" 
  import Header from "../lib/components/Header.svelte"
</script>

<Header />

<slot />

<Hero />