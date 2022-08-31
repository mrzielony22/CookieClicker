<script lang="ts">
    import Cookie from './cookie.svelte'
</script>


<div class="game-container">
    <div class="grid-item cookie-container">
        <Cookie/>
    </div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
</div>

<style lang="less">
    .game-container{
        height: 100%;
        display: grid;
        grid-template-columns: 30% 40% 30%;
    }
    .grid-item{
        background-color: white;
        border: 1px solid green;
    }
    .cookie-container{
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>