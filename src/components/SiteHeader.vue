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
  height: 100px;
  
  .logo{
    display: flex;
    width: 40%;
    align-items: center;
    img{
      height: 80px;
    }

  }
  .navbar{
    display: flex;
    align-items: center;
    width: 60%;
   a{
     text-decoration: none;
     margin: 5px;
     font-weight: 600;
      line-height: 95px;
     &:hover{
       color: #0282F9;
       border-bottom: 5px solid #0282F9;
     }
   }
  }
}
</style>
