<script lang="ts">
	import GameLayout from './components/gameLayout.svelte'
</script>

<GameLayout/>

<style>
	* {
        margin:0px;
        height:100vh;
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