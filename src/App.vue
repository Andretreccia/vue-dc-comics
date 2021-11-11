<template>
  <div id="app">
    <SiteHeader/>
    <!-- /#header -->
    <SiteMain/>
    <!-- /#main -->
    <footer id="site_footer">
      <div class="container">
        <div class="row">
          <div class="container-link">
            <div class="col">
              <h3>DC COMICS</h3>
              <div class="footer-link-list">
                <ul>
                  <li><a href="">Characters</a></li>
                  <li><a href="">Comics</a></li>
                  <li><a href="">Movies</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">Games</a></li>
                  <li><a href="">Videos</a></li>
                  <li><a href="">News</a></li>
                </ul>
              </div>
              <h3>SHOP</h3>
              <div class="footer-link-list">
                <ul>
                  <li><a href="">Shop DC</a></li>
                  <li><a href="">Shop DC Collectibles</a></li>
                </ul>
              </div>
            </div>
            <div class="col">
              <h3>DC</h3>
              <div class="footer-link-list">
                <ul>
                  <li><a href="">Term Of Use</a></li>
                  <li><a href="">Privacy policy (New)</a></li>
                  <li><a href="">Ad Choices</a></li>
                  <li><a href="">Advertising</a></li>
                  <li><a href="">Jobs</a></li>
                  <li><a href="">Subscriptions</a></li>
                  <li><a href="">Talent Workshops</a></li>
                  <li><a href="">CPSC Certificates</a></li>
                  <li><a href="">Ratings</a></li>
                  <li><a href="">Shop Help</a></li>
                  <li><a href="">Contact Us</a></li>
                </ul>
              </div>
            </div>
            <div class="col">
              <h3>SITES</h3>
              <div class="footer-link-list">
                <ul>
                  <li><a href="">DC</a></li>
                  <li><a href="">MAD Magazine</a></li>
                  <li><a href="">DC Kids</a></li>
                  <li><a href="">DC Universe</a></li>
                  <li><a href="">DC Power Visa</a></li>
                </ul>
              </div>
              </div>      
          </div>
        </div>
      </div>
    </footer>
    <!-- /#footer -->
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";

export default {
  name: "App",
  components: {
   SiteHeader,
   SiteMain,
  },
};
</script>

<style lang="scss">
#app{
  font-family: "Greta Sans Medium","Greta Sans Regular",Arial,sans-serif;

.container{
  margin: auto;
  max-width: 1200px;
}
.row{
  display: flex;

}
}
#site_footer{
  height: 400px;
  background-image: url(./assets/img/footer-bg.jpg);
  .container-link{
    display: flex;
    flex-direction: row;
    .col{
      width: 170px;
      h3{
        color: white;
      }
      .footer-link-list{
        ul{
          list-style: none;
          padding: 0;
          li{
            margin: 5px 0;
            a{
            text-decoration: none;
            color:#959595;
            &:hover{
              color: white;
            }
          }
          }

        }
      }
    }
  }
}
</style>
