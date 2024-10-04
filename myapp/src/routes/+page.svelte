<script>
	import Slider from '@bulatdashiev/svelte-slider';

	let range = [20, 70];
	let range2 = [30, 40];
</script>


<div class="p-4 bg-slate-500 rounded">
  <Slider class="bg-black text-white"/>
</div>


<div class="p-4 bg-slate-500 rounded">
  <Slider max="200" step="10" bind:value={range2} range order class="bg-blue-900 text-white"/>
</div>

<svelte:head>
	
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css"/>
</svelte:head>
