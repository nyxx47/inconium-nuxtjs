<template>
    <div class="logo-wrap">
        <img :src="image" alt="">
    </div>
</template>

<script>
export default {
    name: "logo",
    props: ["image"]
}
</script>

<style scoped>
img{
    width: auto;
}
</style>


