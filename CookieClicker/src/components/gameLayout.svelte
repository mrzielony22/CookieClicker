<script lang="ts">
    import Cookie from './cookiComponents/cookie.svelte'
    import CookieHeader from './cookiComponents/cookieHeader.svelte'
</script>


<div class="game-container">
    <div class="grid-item cookie-container cookie-background">
        <CookieHeader/>
        <Cookie/>
    </div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
</div>

<style lang="less">
    .game-container{
        height: 100%;
        display: grid;
        grid-template-columns: 25% 45% 30%;
    }
    .grid-item{
        border: 1px solid green;
    }
    .cookie-container{
        display: flex;
        justify-content: center;
        align-items: center;
        border: 3px groove brown;
    }
    .cookie-background{
        background-image: url('./coo.png');
        background-size: cover;
        width: 100%;
        height: 100%;
    }
</style>