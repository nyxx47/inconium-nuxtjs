<template>
  <div id="container-app">
    <nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

@media only screen 
  and (min-width: 320px) 
  and (max-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2) {

    .wrapper{
      display: none;
    }

    ul#social-wrapper{
      display: none;
    }

    ul#social-wrapper li{
      margin-left: 20px !important;
    }

    #landing{
      background: radial-gradient(1192.10px at 0% 1.24%, #3D3F65 0%, #202135 100%) !important;
    }

    .second-section{
      width: 80% !important;
      margin-top: 60px !important;
    }

    .head .title h1{
      font-size: 32px !important;
    }

    .head .title h1 span{
      font-size: 32px !important;
    }

    .logo-wrap{
      display: none;
    }

    .footer-responsive{
      display: inline-block !important;
    }

    .description p{
      font-size: 11px !important;
      top: -35px !important;
    }

    .footer{
      margin-top: 15px !important;
    }

    .hero-text{
      top: -30px !important;
    }

    .create{
      font-size: 12px !important;
    }
    .design{
      font-size: 12px !important;
    }
    .code{
      font-size: 12px !important;
    }
    .build{
      font-size: 12px !important;
    }
    

    .menu-icon{
      display: inline-block !important;
    }
}
</style>
