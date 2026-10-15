<script>

	import favicon from '$lib/assets/favicon.svg';
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import "$lib/assets/global-styles.css";
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<!-- <link rel="stylesheet" href={styles}/> -->
</svelte:head>

<Header />

{@render children()}

<Footer />

<style>
	
</style>