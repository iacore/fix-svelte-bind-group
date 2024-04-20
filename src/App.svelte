<script>
	let name = ['existing option'];
</script>

<h1>Refresh to reset</h1>
<h1>{JSON.stringify(name)}</h1>
Try click on these:
<input type="checkbox" value="no" bind:group={name}>
<input type="checkbox" value="yes" bind:group={name}>