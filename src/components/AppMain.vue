<script >

export default{
  name: 'AppMain'
}

</script>
<template>
    <div id="back">
        <div class="d-flex flex-column">
            <h2>DC COMICS</h2>
            <ul>
                <li>Character</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <h2>DC COMICS</h2>
            <ul>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
                
                
            </ul>
            
        </div>
        <div class="ms-4">
            <h2>DC </h2>
            <ul>
                <li>Term</li>
                <li>Privacy</li>
                <li>Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Sub</li>
                <li>Talent</li>
                <li>CP</li>
                <li>Ratings</li>
                <li>Shop</li>
                <li>Contacts</li>
            </ul>
        </div>
        <div class="ms-4">
            <h2>DC COMICS</h2>
            <ul>
                <li>DC</li>
                <li>MAD</li>
                <li>DCk</li>
                <li>DCu</li>
                <li>DC pow</li>
                
            </ul>
        </div> 
        <div id="logo" class="position-absolute">
            <img class="position-absolute" src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
    
   
</template>
<style lang="scss" scoped >
#back{
    display: flex;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 370px;
    width: 100.45%;
    margin: -8px;
    color: white;
    padding-left: 300px;
    padding-top: 50px;
    position: relative;
    overflow: hidden;
    h2{
        font-size: 20px;
        font-weight:bold;
    }
}
ul{
    list-style: none;
    padding: 0%;
    color: lightgrey;
}
#logo{
    top: -100px;
    right: 900px;
}


</style>