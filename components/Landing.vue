<template>
    <div id="landing">
        <div class="header">
            <Logo :image="img"></Logo>
            <Social></Social>
            <div class="menu-icon">
                <div class="first"></div>
                <div></div>
            </div>
        </div>
        <div class="second-section">
            <Left></Left>
            <Right></Right>
        </div>
        <div class="footer-responsive">
            <ul>
                <li><img src="ig.svg" alt="" srcset=""></li>
                <li><img src="fb.svg" alt="" srcset=""></li>
                <li><img src="linkedin.svg" alt="" srcset=""></li>
            </ul>
        </div>
    </div>
</template>

<script>
import Logo from '~/components/logo.vue';
import Social from '~/components/social.vue';
import Left from '~/components/left.vue';
import Right from '~/components/right.vue';

export default {
    data(){
        return{
            img: '/logo.svg'
        }
    },
    components: {
        Logo,
        Social,
        Left,
        Right
    }
}
</script>

<style>
#landing{
    background: url('/Intersect.svg'), radial-gradient(1192.10px at 0% 1.24%, #3D3F65 0%, #202135 100%);
    background-repeat: no-repeat;
    background-size: contain;
    width: 100%;
    height: 100vh;
}

.menu-icon{
    display: none;
    width: 90%;
    min-height: 50px;
    margin: 0 auto;
    margin-top: 30px;
}

.footer-responsive{
    display: none;
    position: absolute;
    bottom: 8%;    
}

.footer-responsive ul li{
    display: inline;
    margin-right: 30px;
}

.footer-responsive ul li img{
    width: auto !important;
}

.menu-icon div{
    width: 10%;
    height: 2px;
    background: white;
    margin-bottom: 8px;
    opacity: 0.3;
}

.menu-icon .first{
    width: 7% !important;
}

.header {
    display: flex;
    justify-content: space-between;
    width: 90%;
    margin: 0 auto;
    line-height: 150px;
}

.second-section{
    display: flex;
    justify-content: space-between;
    width: 90%;
    margin: 0 auto;
}
</style>

