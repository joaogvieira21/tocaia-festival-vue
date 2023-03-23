<template>
    <div class="img-container">
        <FundoImg>
        </FundoImg>
    </div>
</template>

<script>
    import TitlePre from '../atoms/TitlePre.vue';
    import FundoImg from '../atoms/FundoImg.vue'
    import Img from '../atoms/Img.vue';
    export default {
        data() {
            return {
                img: '../../public/img/foto4.jpg'
            }
        },
        components: {
            FundoImg,
            Img,
            TitlePre
        }
    }
</script>

<style>
    .img-container {
        width: 45%;
    
    }


</style>