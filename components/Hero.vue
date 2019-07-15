<template>
    <div id="hero">
        <div class="wrapper">
            <div class="hero-wrapper">
                 <h1>INCONIUM</h1>
            </div>
            <div class="hero-text">
                <p class="slogan"><span class="create">Create</span>.<span class="design">Design</span>.<span class="code">Code</span>.<span class="build">Build</span></p>
            </div>
            <div class="progress-bar"></div>
        </div>
    </div>
</template>

<script>
export default {

  mounted(){

    function loadBar(){
                let n = 100;
                for(let i=0; i<=n; i++){
                    setTimeout(function(){
                        $('head').append('<style>.progress-bar:before{width:'+i+'% !important;}</style>');
                    },10000)
                    
                }
            }

            loadBar()

                    window.addEventListener("load", function(){
                        console.log("load is good")
                        setTimeout(function(){
                         var audio = new Audio('MenuContinue.ctOS.wav');
                            audio.play();
                            
                    }, 1100)
                    })
    }

}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:300,400,500&display=swap');

#hero{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hero-text {
    display: inline;
    position: relative;
    top: -20px;
}

.progress-bar{
    width: 150px;
    height: 3px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 30px;
    position: relative;
    left: 5px;
    top: -10px;
    transition: 10s ease;
}

.progress-bar::before{
    content: '';
    width:0;
    height: 3px;
    background: #97F688;
    position: absolute;
    transition: 10s ease;
    border-radius: 30px;
}

h1{
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 48px;
    line-height: 59px;
    letter-spacing: 0.35px;
    color: #DADADA;
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
    font-size: 14px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #97F688;
    padding-right: 3px;   
}

.design{
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #88D5F6;
    padding-right: 3px;
    padding-left: 3px;
}

.code{
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #F68888;
    padding-right: 3px;
    padding-left: 3px;
}

.build{
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 57px;
    letter-spacing: 0.35px;
    color: #F4F688;
    padding-left: 3px;
}

</style>
