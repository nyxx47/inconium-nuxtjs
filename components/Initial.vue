<template>
    <div id="container">
        <Hero></Hero>
    </div>
</template>

<script>
import Hero from '~/components/Hero.vue';
export default {
    components: {
        Hero
    }
}
</script>

<style>
    #container{
        width: 100%;
        height: 100vh;
        background: radial-gradient(1192.10px at 0% 1.24%, #3D3F65 0%, #202135 100%);
    }
</style>

