<script>
	let count = 0;
</script>

<button on:click="{() => count += 1}">+1</button>
<slot count={count}/>