<template>
    <div>  Counted {{likes}}</div>
    <button v-on:click="like">Like me</button>
</template>

<script>
    export default {
        data() {
            return {
                likes: 0,
            }
        },
        methods: {
            like(){ 
                this.likes += 1;
            }
        }
    }
</script>

<style>

</style>
