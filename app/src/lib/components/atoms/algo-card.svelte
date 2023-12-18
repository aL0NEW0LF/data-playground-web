<script>
	import * as Card from '$lib/components/ui/card';
	import Regression from '$lib/icons/regression.svelte';

	/**
	 * @type {String}
	 */
	export let title;
</script>

<Card.Root class="w-88">
	<Card.Content class="p-4">
		<slot name="algo-figure" class="w-auto" />
	</Card.Content>
	<Card.Header class="pt-0">
		<Card.Title class="text-center text-2xl">{title}</Card.Title>
	</Card.Header>
</Card.Root>
