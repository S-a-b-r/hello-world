<template>
    <div class ="v-catalog">
        <h1>{{title}}</h1>
        <vCatalogItem/>
    </div>

</template>

<script>
import vCatalogItem from './v-catalog-item'
export default{
    name: 'v-catalog',
    components: {
        vCatalogItem
    },
    props: {},
    data(){
        return { title: 'catalog'}
    },
    computed: {},
    methods: {},
    watch: {},
    mounted() {
        console.log('hello, v-catalog');
    }
}
</script>

<style>

</style>