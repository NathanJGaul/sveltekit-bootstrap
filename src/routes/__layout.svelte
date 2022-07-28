<script>
	import Header from '$lib/header/Header.svelte';
	import '../app.scss';
	import { onMount } from 'svelte';

	onMount(async () => {
		const bootstrap = await import('bootstrap');
	})
</script>

<main>
	<slot />
</main>

<style>
</style>
