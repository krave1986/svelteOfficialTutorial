<script>
	let count = 0;
	function handleClick() {
		count += 1;
	}
	$: doubled = count * 2;
</script>

<button on:click={handleClick}> Clicked {count} time{count === 1 ? "" : "s"}</button>
<p>{count} doubled is {doubled}</p>

<style>
</style>
