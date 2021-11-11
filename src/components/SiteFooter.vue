<template>
    <footer id="site_footer">
      <div class="footer-container">
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
        <div class="footer-banner">
        </div>
      </div>
      </div>
         <div class="footer-banner">
           <div class="container">
            <div class="row">
              
              <button>SIGN-UP NOW!</button>
            
          <div class="social">
                    <a href="">FOLLOW US</a>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
          </div>
            </div>
         </div>
         </div>
    </footer>
</template>

<script>

</script>

<style lang="scss">
#site_footer{
  .footer-container{
    padding: 1rem 0;
    background: url(../assets/img/dc-logo-bg.png) 68% no-repeat, url(../assets/img/footer-bg.jpg) no-repeat;
    background-size: 550px, cover;

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
  .footer-banner{
    background: #303030;
    .row{
        justify-content: space-between;
        button{
                border: 2px solid #0282f9;
                background: #303030;
                color: white;
                padding: 12px; 
                margin: 21px 0;
        }
        .social{
            display: flex;
            align-items: center;
            img{
                margin: 0 10px;
            }
            a{
                text-decoration: none;
                color: #0282f9;
                font-weight: 600;
                margin-right: 5px;
            }
        }
    }
    
  }

}
</style>
