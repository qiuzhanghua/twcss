<script>
	import './style.css'
  import Counter from './lib/Counter.svelte'
</script>

<main class="m-0 p-1 text-center">
	<h1 class="max-w-none text-red-700 text-6xl leading-tight font-thin bg-blue-400 w-1/2 lg:max-w-[32rem] mx-auto my-auto">
		Hello TailwindCSS!
	</h1>
  <Counter />
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

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
