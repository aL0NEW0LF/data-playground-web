<script>
	/**
	 * @type {any}
	 */
	export let onClick = undefined;
	export let disabled = false;
</script>

<button
	class="p-1 inline-flex items-center justify-center text-sm font-medium whitespace-nowrap hover:text-cod-gray-950 {$$props.class}"
	on:click={onClick}
	{disabled}
>
	<slot />
</button>
