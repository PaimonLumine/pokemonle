<template>
    <section class="app">
        <!-- <HeadMenu></HeadMenu> -->
        <router-view></router-view>
    </section>
</template>

<script>
    import HeadMenu from "./components/HeadMenu.vue";
    export default{
        name:"App",
        components:{
            HeadMenu
        },
        methods:{
            debug(){
            }
        }
    }
</script>

<style>
</style>
