<template>
    <div class ="v-main-wrapper">
        <span>{{title}}</span>
        <vCatalog/>
    </div>

</template>

<script>
import vCatalog from './v-catalog'

export default{
    name: 'v-main-wrapper',
    components: {
        vCatalog
    },
    props: {},
    data(){
        return { title: 'Main wrapper'}
    },
    computed: {},
    methods: {},
    watch: {},
    mounted() {
        console.log('hello');
    }
}
</script>

<style>
.v-main-wrapper{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    max-width: 900px;
    margin: 0 auto;
}
</style>