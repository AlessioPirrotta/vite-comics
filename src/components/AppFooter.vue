<script >

export default{
  name: 'AppFooter'
}

</script>
<template>
    <footer>
        <div>
            <button>SIGN UP NOW</button>
        </div>
        <div class="d-flex align-items-center gap-3">
            <h2>FOLLOW US</h2>
            <img src="../assets/img/footer-facebook.png" alt="">
            <img src="../assets/img/footer-twitter.png" alt="">
            <img src="../assets/img/footer-youtube.png" alt="">
            <img src="../assets/img/footer-pinterest.png" alt="">
        </div>
        
    </footer>
</template>
<style lang="scss" scoped >
footer{
    padding: 40px;
    background-color: #303030;
    height: 120px;
    width: 101%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    button{
        padding: 10px;
        height: 50px;
        background-color: #303030;
        border: 2px solid #0d6efd ;
        text-decoration: none;
        color: white;
    }
}
h2{
    color: #0d6efd;
    font-size: 20px;
    font-weight: bold;
    margin: 0;
}


</style>