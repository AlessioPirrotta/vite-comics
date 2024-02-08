<script >

export default{
  name: 'AppHeader',

data() {
    return {
        arrayNav:['character', 'comic', 'movies', 'tv', 'games', 'collectibles', 'videos', 'fans', 'news', 'shop']
    }
}

}



</script>

<template>
  <div id="main">
    <div>
        <img style="scale: .8;" src="../assets/img/dc-logo.png" alt="">
    </div>
    <nav>
        <ul  v-for="(item, index) in arrayNav" :key="index">
            <li>{{item}}</li>
        </ul>
    </nav>
  </div>
</template>
<style lang="scss" scoped >

#main{
    background-color: white;
    width: 101%;
    height: 120px;
    
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 200px;
    
}
nav{
    display: flex;
}
ul{
    list-style: none;
    text-transform: uppercase;
    font-weight: 600;
}

</style>