<script>
export default {
    
}
</script>
<template>
    <div class="bg-img">
        <div class="container">
            <div class="row">
                <div class="col-6 d-flex py-3">
                    
                </div>
                <div class="col-6 logo-container">
                    <div class="content">
                        <img src="../src/assets/img/dc-logo-bg.png" class="logo" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="bg-footer ">
        <div class="container ">
            <div class="row ">
                <div class="col-6 ">
                    <div class="content py-5">
                        <button class="btn text-light">SIGN-UP NOW!</button>
                    </div>
                </div>
                <div class="col-6 ">
                    <div class="content py-5 d-flex justify-content-center">
                        <h4 class="text-primary ">FOLLOW US</h4>
                         <img src="../src/assets/img/footer-facebook.png">
                         <img src="../src/assets/img/footer-twitter.png">
                         <img src="../src/assets/img/footer-youtube.png">
                         <img src="../src/assets/img/footer-pinterest.png">
                         <img src="../src/assets/img/footer-periscope.png">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.bg-img {
    background-image: url('../src/assets/img/footer-bg.jpg');
    background-size: cover;
    overflow: hidden;

}

.logo-container {
    position: relative;
    overflow: hidden; 
}

.logo {
    width: 600px;
    position: absolute;
    top: 40%;
    left: 50%; 
    transform: translate(-50%, -50%);
    z-index: 2;
}

.bg-footer {
    background-color: #303030;
    z-index: 3;
    

    .btn{
    border-color: #0082F9;
    border-radius: 0;
    padding: 10px;
}
}

.content img{
    margin: 0px 10px;
}
</style>
