<script>
	import MagnifyingGlassIcon from '../../assets/icons/magnifying-glass.svelte';
</script>

<div class="flex flex-row">
	<div class="relative w-full my-2">
		<input
			type="text"
			class="align-middle items-center h-10 rounded-md border border-input bg-background px-3 py-2 text-sm ring-cod-gray-950 text-cod-gray-950 w-96 placeholder:text-cod-gray-500"
			placeholder="Search"
		/>
		<MagnifyingGlassIcon
			class="absolute -translate-y-1/2 top-1/2 right-1 fill-cod-gray-950"
			width="32"
			height="32"
		/>
	</div>
</div>
