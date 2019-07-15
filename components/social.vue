<template>
    <div>
        <ul id="social-wrapper">
            <li><img src="fb.svg" alt="" srcset=""></li>
            <li><img src="linkedin.svg" alt="" srcset=""></li>
            <li><img src="ig.svg" alt="" srcset=""></li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "social"
}
</script>

<style scoped>

ul#social-wrapper{
    float: right;
}

ul#social-wrapper li{
    display: inline;
    margin-left: 40px;
}

#social-wrapper li img{
    width: auto;
}
</style>
