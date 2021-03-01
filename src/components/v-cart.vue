<template>
    <div class ="v-cart">
        <span>{{title}}</span>
    </div>

</template>

<script>
export default{
    name: 'v-cart',
    components: {},
    props: {},
    data(){
        return { title: 'Cart'}
    },
    computed: {},
    methods: {},
    watch: {},
    mounted() {
        console.log('hello, v-cart');
    }
}
</script>

<style>

</style>