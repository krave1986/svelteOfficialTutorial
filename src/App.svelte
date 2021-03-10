<script>
	let count = 1;
	$: {
		console.log(`Before A: ${count}`);
		count = 2;
		console.log(`A: ${count}`);
	}
	$: {
		console.log(`B: ${count}`);
	}
	$: {
		console.log(`Before C: ${count}`);
		count = 3;
		console.log(`C: ${count}`);
	}
	$: {
		console.log(`D: ${count}`);
	}
</script>
