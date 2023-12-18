<script>
	import '$src/app.pcss';
	import './styles.css';
	import Header from '$lib/components/organisms/header.svelte';
</script>

<div class="">
	<Header />
	<main class="mx-96 my-32">
		<slot />
	</main>
</div>
