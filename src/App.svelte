<script>
	import './style.css'
  import Counter from './lib/Counter.svelte'
</script>

<main class="m-0 p-[1em] text-center
font-[-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif]
">
	<h1 class="text-[#ff3e00] text-[4rem] leading-tight font-thin bg-blue-400 w-1/2 max-w-[32rem] mx-auto my-auto rounded-full">
		Hello TailwindCSS!
	</h1>
  <Counter />
</main>

<style>
  /* :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  } */

  /*main {*/
  /*  text-align: center;*/
  /*  padding: 1em;*/
  /*  margin: 0 auto;*/
  /*}*/

  /*h1 {*/
    /*color: #ff3e00;*/
    /*text-transform: uppercase;*/
    /*font-size: 4rem;*/
    /*font-weight: 100;*/
    /*line-height: 1.1;*/
    /*margin: 2rem auto;*/
    /*max-width: 14rem;*/
  /*}*/

  /*@media (min-width: 480px) {*/
  /*  h1 {*/
  /*    max-width: none;*/
  /*  }*/
  /*}*/
</style>
