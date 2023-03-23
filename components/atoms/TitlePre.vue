<template>
    <h1>
        {{title}}
    </h1>
   
</template>

<script>
    export default {
        props: {
            title: String
        }
    }
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,700;1,700&display=swap');
    h1 {
        font-family: 'Roboto Condensed', sans-serif;
        color: white;
        font-size: 6.5em;
        font-weight:500;
        text-transform: uppercase;
      
    }

    
</style>