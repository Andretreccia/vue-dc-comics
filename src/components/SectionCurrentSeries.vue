<template>
    <div class="card"> 
        <img class="card-img" :src="image" alt="">
        <h6 class="card-title">{{title}}</h6>
    </div>
</template>

<script>
export default{
   props: {
        image: String,
        title: String,
   }
}

</script>

<style lang="scss">
.card{
        width: calc(100% /6); 
        text-align: center;
        margin-top: 2rem;

    .card-img{
        height: 160px;
        width: 160px;
        object-fit: cover;
        object-position: top;
    }
    .card-title{
        margin: 10px;
        font-size: 15px;
        color: lightgrey;
        text-align: start;
    }
}

</style>
