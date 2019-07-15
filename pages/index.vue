<template>
  <div id="inconium-app">
    <Initial v-if="isVisible"></Initial>
    <Landing v-else></Landing>
  </div>
</template>

<script>
import Initial from '~/components/Initial.vue';
import Landing from '~/components/Landing.vue';

export default {
  head() { // <-- property used by vue-meta to add header tags
        return {
          htmlAttrs: {
            lang: 'en'
          },
          title: 'INCONIUM - Software HUB', // <-- For our title tag
          meta: [
            {
              hid: 'description',  
              name: 'description', // <-- for our meta description tag
              content:
                'INCONIUM is the central of a software engineer, UI/UX Designer and QA Freelancer that focuses on software development.'
            }
          ]
        }
  },
  data(){
    return{
      isVisible: true
    }
  },
  components: {
    Initial,
    Landing
  }
}
</script>

<style scoped>
#inconium-app{
  width: 100%;
  height: 100vh;
}
</style>
