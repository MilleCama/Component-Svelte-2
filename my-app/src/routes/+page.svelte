<script>
	import Title from './Title.svelte';
	import Control from './Control.svelte'; 
</script>


<Title text="Svelte Component 2" />

<h1 class="text-lg text-center mt-4">Select a Segment</h1>


<Control />

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css" />
</svelte:head>