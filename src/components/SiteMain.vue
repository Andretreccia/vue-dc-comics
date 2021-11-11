<template>
    <main id="site_main">
      
      <section> 
        <div class="container">
          <h1> -->CONTENT GOES HERE  </h1>
        </div>
      </section>
      <div class="shop-comics">
        <div class="container">
          <div class="row">
            <div class="card">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
              
            </div>
            <div class="card">
              <img src="../assets/img/buy-comics-merchandise.png" alt="">
              <span>DC MERCHANDISE</span>
            </div>
            <div class="card">
              <img src="../assets/img/buy-comics-subscriptions.png" alt="">
              <span>SUBSCRIPTION</span>
            </div>
            <div class="card">
              <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="card">
              <img src="../assets/img/buy-dc-power-visa.svg" alt="">
              <span>DC SHOP LOCATOR</span>
            </div>
          </div>
        </div>
      </div>
    </main>
</template>

<script>

</script>

<style lang="scss">
#site_main{
  section{
    height: 100px;
    background-color: #1C1C1C;
    color: white;
  }
  .shop-comics{
    background-color: #0282F9;
    height: 120px;
           .row{
             display: flex;
             justify-content: space-between;
               align-items: center;
               height: 120px;
           
             .card{
               display: flex;
               justify-content: center;
               align-items: center;
                color: white;

                img{
                  width: 40px;
                  margin: 10px;
                }
             }
           } 
  }
}
</style>