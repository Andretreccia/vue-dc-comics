<template>
    <main id="site_main">
      <section> 
        <div class="container">
          <h1> -->CONTENT GOES HERE  </h1>
        </div>
      </section>
     
         <ShopSection/>
    <!-- /#shop_section -->
    </main>
</template>

<script>
import ShopSection from "./ShopSection.vue";
export default{
  components:{
    ShopSection,
  }
}
</script>

<style lang="scss">
#site_main{
  section{
    height: 120px;
    background-color: #1C1C1C;
    color: white;
  }
  
}
</style>