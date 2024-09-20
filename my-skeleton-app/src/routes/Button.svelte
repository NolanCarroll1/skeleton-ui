<script>
	export let name = "Default";
	export let type = "disabled"; // regular, flat, disabled
</script>

{#if type=="regular"}
 <button class={`rounded-full bg--600 bg-purple-600 hover:bg-blue-500 font-bold text-gray-200 px-5 py-3 pr-8 pl-8`}>
  {name}
 </button>
{/if}

{#if type=="flat"}
 <button class={`rounded-full font-bold border border-none  px-5 py-3 pr-8 pl-8`}>
  {name}
 </button>
{/if}

{#if type=="disabled"}
 <button class={`rounded-full font-bold border border-gray-700 text-gray-700 px-5 py-3 pr-8 pl-8`}>
  {name}
 </button> 
{/if}
