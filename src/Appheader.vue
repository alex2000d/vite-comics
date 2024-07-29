<script>
export default {
    
}
</script>
<template lang="">
    <header>
        <div class="container">
            <div class="row">
                <div class="col-4">
                    <div class="p-3 ms-5 align-middle logo-img">
                        <img src="../src/assets/img/dc-logo.png" />
                    </div>
                    
                </div>
                <div class="col-8">
                    <ul class="list-unstyled d-flex mt-4 align-middle">
                        <li>characters</li>
                        <li class="active">comics</li>
                        <li>movies</li>
                        <li>tv</li>
                        <li>games</li>
                        <li>collectibles</li>
                        <li>videos</li>
                        <li>fans</li>
                        <li>news</li>
                        <li>shop</li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>
<style lang="scss" scoped>
.logo-img img{
    max-width: 80px; 
}
   ul {
      li{
        padding: 10px 20px;
      }
   }

   .active{
    color: rgb(42, 147, 252);
   }
</style>