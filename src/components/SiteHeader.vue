<template>
    <header id="site_header">
      <div class="container">
         <div class="row">
              <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <nav class="navbar">
        <a href="">CHARACTERS</a>
        <a href="">COMICS</a>
        <a href="">MOVIES</a>
        <a href="">TV</a>
        <a href="">GAMES</a>
        <a href="">COLLECTIBLES</a>
        <a href="">VIDEOS</a>
        <a href="">FANS</a>
        <a href="">NEWS</a>
        <a href="">SHOP</a>
      </nav>
         </div>
      </div>
    </header>
</template>

<script>

</script>

<style lang="scss">
#site_header{
  height: 120px;
  
  .logo{
    display: flex;
    width: 40%;
    align-items: center;
    img{
      height: 90px;
    }

  }
  .navbar{
    height: 100%;
    display: flex;
    align-items: center;
    width: 60%;
   a{
     font-size: 14px;
     height: 100%;
     text-decoration: none;
     margin-left: 20px;
     font-weight: 600;
     line-height: 130px;
     color: #464646;
     &:hover{
       color: #0282F9;
       border-bottom: 5px solid #0282F9;
     }
   }
  }
}
</style>
