<script>
	import '../app.css';
	import Nav from '$lib/Nav.svelte';
</script>

<div class="wrapper">
	<header id="header" class="box">Hier könnte ein Header sein</header>
	<Nav />
	<main id="main" class="box">
		<slot />
	</main>
	<footer id="footer" class="box">und hier stehen coole links</footer>
</div>

<style>
	.wrapper {
		display: grid;
		grid-template-areas: 'nav header' 'nav main' 'footer footer';
		min-height: 100vh;
		grid-template-columns: 250px 1fr;
		grid-template-rows: auto 1fr auto;
		grid-gap: 0.1rem;
		background-color: black;
	}

	#header {
		grid-area: header;
		text-align: center;
	}

	#main {
		grid-area: main;
	}

	#footer {
		grid-area: footer;
	}

	.box {
		background-color: #474747;
		padding: 1rem;
		font-size: 150%;
		color: white;
	}

	
</style>
