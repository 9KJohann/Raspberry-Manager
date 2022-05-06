<script>
	import '../app.css';
	import Nav from '$lib/Nav.svelte';
</script>

<div class="wrapper">
	<header id="header">Hier könnte ein Header sein</header>
	<Nav />
	<main id="main">
		<slot />
	</main>
	<footer id="footer">und hier stehen coole links</footer>
</div>

<style>
	.wrapper {
		display: grid;
		grid-template-areas: 'nav header' 'nav main' 'footer footer';
		min-height: 100vh;
		grid-template-columns: 250px 1fr;
		grid-template-rows: auto 1fr auto;
		color: var(--fontColor);
		font-size: 1.25rem;
		background-color: var(--backColor);
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

	

	
</style>
