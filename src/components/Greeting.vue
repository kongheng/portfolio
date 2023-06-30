<template>
    <h1>{{ msg }}</h1>
    <img src="../assets/profile.png">
</template>

<script>
    export default {
        name: 'MyGreeting',
        props: {
            img: String,
            msg: String
        }
    }
</script>

<style scoped>
    h1 {
    color: purple;
    }   
</style>