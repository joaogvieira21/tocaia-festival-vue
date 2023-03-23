<template>
    <section>
        <PreVenda></PreVenda>
        <ImgContainer></ImgContainer>
    </section>    
</template>

<script>
    import PreVenda from '../molecules/PreVenda.vue';
    import ImgContainer from '../molecules/ImgContainer.vue';
    export default {
        components: {
            PreVenda,
            ImgContainer
        }
    }

</script>

<style>
    section {
        min-height: 79vh ;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        gap: 50px;
    }

  
    

</style>