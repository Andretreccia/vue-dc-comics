<template>
  <div id="app">
    <SiteHeader/>
    <!-- /#site_header -->
    <SiteMain/>
    <!-- /#site_main -->
    <ShopSection/>
    <!-- /#shop_section -->
    <SiteFooter/>
    <!-- /#site_footer -->
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";
import ShopSection from "./components/ShopSection.vue";
import SiteFooter from "./components/SiteFooter.vue";


export default {
  name: "App",
  components: {
   SiteHeader,
   SiteMain,
   ShopSection,
   SiteFooter,
  },
};
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app{
  font-family: "Greta Sans Medium","Greta Sans Regular",Arial,sans-serif;

.container{
  margin: auto;
  height: 100%;
  max-width: 1200px;
  .row{
  display: flex;
  height: 100%;

  }
}
}

</style>
