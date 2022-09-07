<script lang="ts">
	import GameLayout from './components/gameLayout.svelte'
</script>

<GameLayout/>

<style>
	:global(body) {
		background-color: #3c3c3c;
		transition: background-color 0.3s
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>