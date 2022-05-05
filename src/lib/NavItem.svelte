<script lang="ts">
	export let name: string;
	export let path: string;
</script>

<li>
	<a href={path}>
		<span class="material-symbols-outlined">home</span>
		{name}
	</a>
</li>

<style>
	a {
		display: block;
		width: auto;
		height: 1.5em;
		text-align: left;
        text-decoration: none;
		color: white;
	}

	span {
		margin-left: 0.2em;
		padding: 5px;
	}

	li:hover {
		background-color: #4157d1;
	}
	li {
		border: 1px #363636 solid;
	}
	
</style>
