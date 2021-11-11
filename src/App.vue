<template>
  <div id="app">
    <SiteHeader/>
    <!-- /#header -->
    <div id="main"></div>
    <!-- /#main -->
    <div id="footer"></div>
    <!-- /#footer -->
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";

export default {
  name: "App",
  components: {
   SiteHeader,
  },
};
</script>

<style lang="scss">
#app{
  font-family:  Roboto, sans-serif;
}

</style>
