<script>
	// export let name;
	let saludo = "Hola Silvi y Ana"
	let contador = 0
	const aumentar = () => {
		contador ++;
	}
</script>

<main>
	<h1>{saludo}</h1>
	<h2>contador: {contador}</h2>
	<button on:click={aumentar}>Aumentar</button>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>