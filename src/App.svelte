<script>
	let count = 0;
	function handleClick() {
		count += 1;
	}
</script>

<button on:click={handleClick}> Clicked {count} time{count === 1 ? "" : "s"}</button>

<style>
</style>
