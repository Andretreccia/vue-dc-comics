<template>
    <main id="site_main">
      <div class="jumbotron">
        <img src="../assets/img/jumbotron.jpg" alt="">
      </div>
      <div class="current-series-section"> 
        <div class="container current-series-container">
            <button class="current-series-btn">CURRENT SERIES</button>
          <div class="row current-series-row">
            <SectionCurrentSeries v-for="currentSerie in currentSeries" :key="currentSerie.serie" :image="currentSerie.thumb" :title="currentSerie.series"/>
          <button class="load-more">LOAD MORE</button>
          </div>
        </div>
      </div>
     
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
  },
  data(){
    return {
      currentSeries: [
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$2.99",
    "series": "Batman Beyond",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
    "price": "$3.99",
    "series": "Batman/Superman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
    "price": "$4.99",
    "series": "Batman/Superman Annual",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
    "price": "$5.99",
    "series": "Batman: The Joker War Zone",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
    "price": "$6.99",
    "series": "Batman: Three Jokers",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
    "price": "$4.99",
    "series": "Batman: White Knight Presents: Harley Quinn",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
    "price": "$16.99",
    "series": "Catwoman",
    "type": "graphic novel"
  }
]
    }
  }
}
</script>

<style lang="scss">
#site_main{
  .jumbotron img{
    height: 400px;
    width: 100%;
    overflow: hidden;
    width: 100%;
    object-fit: cover;
    object-position: top;
    display: block;

      
  }
  .current-series-section{
    background-color: #1C1C1C;
    color: white;
    .current-series-container{
      position: relative;
      .current-series-btn{
                border: 2px solid #0282f9;
                background: #0282f9;
                color: white;
                padding: 12px 16px; 
                font-size: 16px;
                cursor: pointer;
                font-weight: 600;
                position: absolute;
                top: -22px;
                left: 0;
    }
  .current-series-row{
    padding:  30px 0 ;
    flex-wrap: wrap;
    justify-content: space-around;
    width: 100%; 
      .load-more{
                margin-top: 50px;
                border: 2px solid #0282f9;
                background: #0282f9;
                color: white;
                padding: 12px 70px; 
                font-size: 16px;
                cursor: pointer;
                font-weight: 600;
      }
  }
    }
  }
  
}
</style>