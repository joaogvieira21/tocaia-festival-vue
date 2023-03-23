<template>
    <div class="header">
        <Logo></Logo>
        <Navbar></Navbar>
    </div>
</template>

<script>
    import Logo from '../atoms/Logo.vue';
    import Navbar from '../molecules/Navbar.vue';
    export default {
        components: {
            Logo,
            Navbar
        }
    }
</script>

<style>
    .header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 21vh; /* Altura do cabeçalho */
        color: #fff; /* Cor do texto do cabeçalho */
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
</style>