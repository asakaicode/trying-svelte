<script>
	let count = $state(0);

	const handleClick = () => {
		count += 1;
	};
</script>

<button onclick={handleClick}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>
