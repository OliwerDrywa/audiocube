<script>
  import logo from "./assets/svelte.png";
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <!-- hint - <audio /> can be used similarly to <img /> -->
  <img src={logo} alt="Svelte Logo" />
  <h1>eło</h1>

  <Counter />

  <p>
    oficjalny i zajebisty
    <a href="https://svelte.dev/tutorial/basics">tutorial svelte</a>
    polecam
  </p>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  img {
    height: 16rem;
    width: 16rem;
  }

  h1 {
    color: #ff3e00;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  a {
    color: #ff3e00;
  }
</style>
