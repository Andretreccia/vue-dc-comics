<template>
     <div id="shop_comics">
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
              <span>DC POWER VISA</span>
            </div>
          </div>
        </div>
      </div>
</template>

<script>

</script>

<style lang="scss">
#shop_comics{
    background-color: #0282F9;
    height: 150px;
           .row{
             padding: 0 16px;
             display: flex;
             justify-content: space-between;
               align-items: center;
               height: 120px;
           
             .card{
               display: flex;
               justify-content: center;
               align-items: center;
                color: white;
                cursor: pointer;

                img{
                  width: 40px;
                  margin: 10px;
                }
                span{
                  font-size: 15px;
                }
             }
           } 
  }
</style>