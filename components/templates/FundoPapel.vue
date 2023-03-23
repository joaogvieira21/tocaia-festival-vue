<template>
    <div>
        <div class="bg-img">
            <Header class="teste"></Header>
            <Main class="section"></Main>
            <BgColor class="bg-color"></BgColor>  
        </div>
        
    </div>
</template>

<script>
    import BgColor from '../atoms/BgColor.vue'
    import Header from '../organisms/Header.vue'
    import Main from '../organisms/Main.vue'
    export default {
        components: {
            BgColor,
            Header,
            Main
        }
        
    }
</script>

<style scoped>
    .bg-img {
        background-image: url('/img/paper.webp');
        background-size: cover;
        background-position: center;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .teste {
        color: white;
        z-index: 2
    }

    .section {
        z-index: 2;
        min-height: 100vh;
        width: 100%;
    }
  
</style>