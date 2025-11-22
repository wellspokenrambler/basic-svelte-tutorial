<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<a href="/" class="p-1 border-2 border-green-500 absolute top-0 left-0 z-10">Home</a>
{@render children()}
