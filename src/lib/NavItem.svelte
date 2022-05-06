<script lang="ts">
	export let name: string;
	export let path: string;
	export let icon: string;
</script>

<li>
	<a href={path}>
		<span class="material-symbols-outlined">{icon}</span>
		{name}
	</a>
</li>

<style>
	a {
		display: flex;
		align-items: center;
		width: auto;
		height: 1.5em;
		text-align: left;
        text-decoration: none;
		color: white;
		padding-top: 0.75rem;
		padding-bottom: 0.75rem;

	}

	span {
		margin-left: 0.2em;
		padding: 5px;
	}

	li:hover {
		background-color: #4157d1;
	}
	
	
</style>
