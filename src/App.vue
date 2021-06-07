<template>
  <div id="app">
    <Loader></Loader>
    <ComingSoon></ComingSoon>
  </div>
</template>

<script>

import ComingSoon from './components/helpers/ComingSoon';
import Loader from "./components/helpers/Loader";

export default {
  components: {
    ComingSoon,
    Loader
  },

  data() {
    return {
    }
  },
  
  methods: {  
  },
  
  created() {
  }
}
</script>


<style lang="scss">
@import "./assets/scss/global.scss";
@import "./assets/scss/button.scss";
</style>
