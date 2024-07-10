<script>
  import KRLogo from "./assets/KR-logo.webp";
  import Counter from "./lib/Counter.svelte";
  import Portfolio from "./lib/Portfolio.svelte";
  import Date from "./lib/Date.svelte";
  import Toaster from "./lib/Toaster.svelte";
  // let date;
</script>

<!-- <Toaster /> -->
<Date />

<main>
  <div>
    <img src={KRLogo} class="logo" alt="Vite Logo" />
  </div>
  <h1>Kirby Robinson</h1>
  <h2>Full Stack Developer</h2>

  <Portfolio />

  <div class="card">
    <Counter />
  </div>
</main>

<style>
  h1,
  h2 {
    color: rgb(40, 40, 40);
  }
  .logo {
    display: none;
    height: 6em;
    /* padding: 1.5em; */
    will-change: filter;
    transition: filter 300ms;
    border: 1px solid darkgrey;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #b1b4f0aa);
  }
</style>
