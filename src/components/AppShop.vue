<script >

export default{
  name: 'AppShop',

  data() {
    return {
        arrayShop:[
            {
                image:'../assets/img/buy-comics-digital-comics.png',
                text:'digital comic'
            },
            {
                image:'../assets/img/buy-comics-digital-comics.png',
                text:'dc merchandise'
            },
            {
                image:'../assets/img/buy-comics-digital-comics.png',
                text:'subscription'
            },
            {
                image:'../assets/img/buy-comics-digital-comics.png',
                text:'comic shop locator'
            },
            {
                image:'../assets/img/buy-comics-digital-comics.png',
                text:'dc power visa'
            },
        ]

        
    }
  },
}

</script>
<template>
    <div id="center" class="bg-primary d-flex justify-content-center">
        <div class="d-flex justify-content-center align-items-center" >
            <img src="../assets/img/buy-comics-digital-comics.png"   alt="">
            <span class="text-uppercase text-light">digital comic</span>
        </div>
        <div class="d-flex justify-content-center align-items-center" >
            <img src="../assets/img/buy-comics-merchandise.png"   alt="">
            <span class="text-uppercase text-light">dc merchandise</span>
        </div>
        <div class="d-flex justify-content-center align-items-center" >
            <img src="../assets/img/buy-comics-subscriptions.png"   alt="">
            <span class="text-uppercase text-light">subscription</span>
        </div>
        <div class="d-flex justify-content-center align-items-center" >
            <img src="../assets/img/buy-comics-shop-locator.png"   alt="">
            <span class="text-uppercase text-light">comic shop locator</span>
        </div>
        <div id="last" class="d-flex justify-content-start align-items-center" >
            <img id="lastImg" src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span style="" class="text-uppercase text-light ">dc power visa</span>
        </div>
    </div>
</template>
<style lang="scss" scoped >
#center{height: 150px;
    width: 101%;
}
img{
    scale: .5;
}
#last{
    width: 300px;
}
#lastImg{
    width: 50%;
}


</style>