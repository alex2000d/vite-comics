<script>
export default {
    data(){
        return{
           comics: [
          {
               thumb: "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
               price: "$19.99",
               series: "Action Comics",
               type: "comic book"
          },
          {
               thumb: "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
               price: "$3.99",
               series: "American Vampire 1976",
               type: "comic book"
          },
          {
               thumb: "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
               price: "$16.99",
               series: "Aquaman",
               type: "graphic novel"
          },
          {
               thumb: "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
               price: "$2.99",
               series: "Batgirl",
               type: "comic book"
          },
          {
               thumb: "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
               price: "$3.99",
               series: "Batman",
               type: "comic book"
          },
          {
              thumb: "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
              price: "$2.99",
              series: "Batman Beyond",
              type: "comic book"
          },
          {
              thumb: "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
              price: "$3.99",
              series: "Batman/Superman",
              type: "comic book"
           },
           {
               thumb: "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
                price: "$4.99",
                series: "Batman/Superman Annual",
                type: "comic book"
           },
           {
                thumb: "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
                price: "$5.99",
                series: "Batman: The Joker War Zone",
                type: "comic book"
           },
           {
                thumb: "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
                price: "$6.99",
                series: "Batman: Three Jokers",
                type: "comic book"
           },
           {
                thumb: "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
                price: "$4.99",
                series: "Batman: White Knight Presents: Harley Quinn",
                type: "comic book"
           },
           {
                thumb: "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
                price: "$16.99",
                series: "Catwoman",
                type: "graphic novel"
           }
          ],
        }  
    },
}
</script>
<template lang="">
        <div class="jumbotron">
            <span class="badge text-bg-primary rounded-0 px-4 py-2">
                <h3>CURRENT SERIES</h3>
            </span>
        </div>
    <div class="bg-dark">
        <div class="container">
            <div class="row pt-5">
                <div class="col-2 " v-for="comic, index in comics" :key="index">
                    <div class="m-2">
                        <img class="image" :src="comic.thumb" :alt="comic.series">
                        <p class="text-white">{{comic.series}}</P>
                    </div>
                </div> 
                <div class="text-center py-2">
                    <button class="btn btn-primary rounded-0 px-5">LOAD MORE</button>
                </div>
            </div>
        </div>
    </div>
    <div class="bg-primary">
        <div class="container">
           <div class="row">
               <div class="col-12 p-5 text-center image z-index">
                   <img src="../src/assets/img/buy-comics-digital-comics.png" />
                   <span class="text-white"> digital comics</span>
                   <img src="../src/assets/img/buy-comics-merchandise.png" />
                   <span class="text-white"> dc merchandise</span>
                   <img src="../src/assets/img/buy-comics-subscriptions.png" />
                   <span class="text-white"> subscription</span>
                   <img src="../src/assets/img/buy-comics-shop-locator.png" />
                   <span class="text-white"> comic shop locator</span>
                   <img src="../src/assets/img/buy-dc-power-visa.svg" />
                   <span class="text-white"> dc power visa</span>
               </div>
           </div>
       </div>
    </div>

    
</template>
<style lang="scss" scoped>
    
    .image img{
        max-width: 40px;
    }

    span{
        padding-right: 90px;
    }

    .z-index{
        position: relative;
        overflow: hidden;
    }
    
    .jumbotron{
         background-image: url('../src/assets/img/jumbotron.jpg');
         background-size: cover;
         height: 300px;
         position: relative;

         .badge{
            position: absolute;
            bottom: -25px;
            left: 90px;
         }
    }

    

    .image{
        height: 250px;
        width: 100%;
    }

    
    
</style>