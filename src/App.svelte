
{#each menu as flavour}
	<Flavour {flavour}/>
{/each}

<script>
	import Flavour from "./Flavour.svelte"
	let menu = [
		'Cookies and cream',
		'Mint choc chip',
		'Raspberry ripple'
	];
</script>