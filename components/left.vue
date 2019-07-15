<template>
    <div>
        <div class="badge">
            <p>DevHub</p>
        </div>
        <div class="head">
            <div class="title">
                <h1>Software <span>HUB</span></h1>
            </div>
            <div class="hero-text">
                <p class="slogan"><span class="create">Create</span>.<span class="design">Design</span>.<span class="code">Code</span>.<span class="build">Build</span></p>
            </div>
            <div class="description">
                <p>INCONIUM is the central of a software engineer and Designer Freelance
                that focuses on software development.</p>
            </div>
            <div class="footer">
                <Button></Button>
            </div>
        </div>
    </div>
</template>

<script>
import Button from "~/components/button.vue"
export default {
    name:"left",
    components: {
        Button
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,500,600&display=swap');
@import url('https://fonts.googleapis.com/css?family=Quicksand:300,400,500,700&display=swap');

.badge{
    margin-top: 25px;
}

.badge p{
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: bold;
        font-size: 10px;
        line-height: 10px;
        max-width: 100px;
        padding: 6px 24px 6px 24px;
        text-align: center;
        letter-spacing: 0.35px;
        color: #45AFE3;
        background: rgba(69, 175, 227, 0.1);
        border-radius: 50px;
}

.head{
    margin-top: 15px;
}

.head .title h1{
    font-family: 'Quicksand', sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 52px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #FFFFFF;
}

.head .title h1 span{
    font-family: 'Quicksand', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 52px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #FFFFFF;
}

.hero-text {
    display: inline;
    position: relative;
    top: -15px;
    left: -3px;
}

.slogan{
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #FFFFFF;
    position: relative;
    left: 5px;
}

.create{
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #97F688;
    padding-right: 3px;   
}

.design{
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #88D5F6;
    padding-right: 3px;
    padding-left: 3px;
}

.code{
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #F68888;
    padding-right: 3px;
    padding-left: 3px;
}

.build{
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #F4F688;
    padding-left: 3px;
}

.description{
    width: 70%;
}

.description p{
    position: relative;
    top: -12px;
    font-family: 'Quicksand', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.35px;
    color: #A7A9BC;
    padding-left: 3px;
}

.footer{
    margin-top: 50px;
}
</style>


