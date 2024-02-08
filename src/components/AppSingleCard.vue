<script >

export default{
  name: 'AppSingleCard',
  props:{
    imge: String,
    text: String
  }
}

</script>
<template>
    <div id="card" class="">
        <figure>
            <img class="" :src="imge" alt="">
        </figure>
        <p>{{text}}</p>
       
    </div>
</template>
<style lang="scss" scoped >
#card{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 120px;


}
img{
    width: 100px;
}
figure{ color: white;
    width: 100px;
    aspect-ratio: 1;
    overflow: hidden;
}
p{
    font-size: 10px;
    margin: 0;
    height: 20px;
}


</style>