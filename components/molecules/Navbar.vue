<template>
    <nav>
        <ul>
            <NavItem  class="li" v-for="(i, index) in items" :key="index" :item="i"></NavItem>
        </ul>
    </nav>
</template>

<script>
    import NavItem from '../atoms/NavItem.vue';
    export default {
        data() {
            return {
                items: [
                    "Home",
                    "About",
                    "Events",
                    "Gallery",
                    "Contact"
                ]
            }
        },
        components: {
            NavItem
        }
    }
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,700;0,900;1,700;1,900&display=swap');

    ul {
        display: flex;
        list-style: none;
    }

    .li {
        width:20%;
        padding: 20px;
        cursor: pointer;
        text-transform: uppercase;
        font-weight: bolder;
        font-family: 'Lato', sans-serif;
        cursor: pointer;

    }

    
</style>