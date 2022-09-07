<script lang="ts">
</script>

<div class="cookie-container">
    <div class="cookie">
    </div>
</div>

<style lang="less">
    .cookie-container{
        display: flex;
        justify-content: center;
        align-items: center;
        background-image: url('./c.png');
        transition: transform .2s;
        &:hover{
            cursor: pointer;
            transform: scale(1.1);
            transition: 0.2s;
        }
    }
    .cookie{
        width: 250px;
        height: 250px;
        &:hover{
            cursor: pointer;
            transform: scale(0.7);
        }
    }
</style>