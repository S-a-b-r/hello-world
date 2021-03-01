<template>
    <div class ="v-catalog-item">
        <span>{{title}}</span>
    </div>

</template>

<script>
export default{
    name: 'v-catalog-item',
    components: {},
    props: {},
    data(){
        return { title: 'catalog-item'}
    },
    computed: {},
    methods: {},
    watch: {},
    mounted() {
        console.log('hello, v-catalog-item');
    }
}
</script>

<style>

</style>