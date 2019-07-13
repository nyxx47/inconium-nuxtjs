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

<style>

</style>
