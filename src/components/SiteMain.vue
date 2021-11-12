<template>
    <main id="site_main">
      <div class="jumbotron">
        <img src="../assets/img/jumbotron.jpg" alt="">
      </div>
      <section> 
        <div class="container">
         <SectionCurrentSeries/>
        </div>
      </section>
     
         <ShopSection/>
    <!-- /#shop_section -->
    </main>
</template>

<script>
import ShopSection from "./ShopSection.vue";
import SectionCurrentSeries from "./SectionCurrentSeries.vue";
export default{
  components:{
    ShopSection,
    SectionCurrentSeries,
  }
}
</script>

<style lang="scss">
#site_main{
  .jumbotron{
    height: 400px;
    width: 100%;
    overflow: hidden;
      img{
        width: 100%;
      }
  }
  section{
    height: 120px;
    background-color: #1C1C1C;
    color: white;
  }
  
}
</style>