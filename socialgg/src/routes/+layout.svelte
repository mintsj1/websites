<script>
	import favicon from '$lib/assets/favicon.svg';
	import Nav from '$lib/components/nav.svelte';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<h1>InstaBook</h1>
<Nav />

{@render children?.()}

<style>
    :global(body) {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
</style>