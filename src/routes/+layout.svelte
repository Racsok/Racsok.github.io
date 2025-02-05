<script>
	import '../app.css';
	let { children } = $props();
</script>

<svelte:head>
	<title>Mi Portafolio</title>
</svelte:head>

{@render children()}
