<template>
    <Header/>

</template>

<script>
    import Header from '../components/Header.vue'
    export default {
        name: 'Index',
        components: {Header},
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
