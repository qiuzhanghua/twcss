<script>
	import '../style.css';

  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment} class="bg-[#ff3e00]/10 text-[#ff3e00]
				w-[200px] mt-4 px-[1em] py-[2em] rounded-[2em] border-2 tabular-nums
				border-solid border-[#ff3e00]/0 outline-none cursor-pointer
				active:bg-[#ff3e00]/20 focus:border-[#ff3e00]">
  Clicks: {count}
</button>

<style>
  /* button { */
    /* font-family: inherit;
    font-size: inherit; */
    /*padding: 1em 2em;*/
    /*color: #ff3e00;*/
    /*background-color: rgba(255, 62, 0, 0.1);*/
    /*border-radius: 2em;*/
    /*border: 2px solid rgba(255, 62, 0, 0);*/
    /*outline: none;*/
    /*width: 200px;*/
    /*font-variant-numeric: tabular-nums;*/
    /*cursor: pointer;*/
  /* } */

  /* button:focus {
    border: 2px solid #ff3e00;
  } */

  /*button:active {*/
  /*  background-color: rgba(255, 62, 0, 0.2);*/
  /*}*/
</style>
