<template>
  <div>
      <div class="productsList">
          <div class="centerArea">
              <div class="productContent">
                  <div class="topArea">
                      <div class="imgArea">
                          <img :src="imgSrc[imgIndex]" class="fullSizeImage"/>
                      </div>
                  </div>
              </div>

          </div>
          <div v-for="i in 5" :key="i" class="productArea">
              <div>
                  <img src="/kahhvecom.imgix.net/urunler/92_1604665685_IpH.jpg?h=750&ixlib=php-1.0.6&lossless=1&w=750&s=61c4196082c042619077e9fee599c617" alt="">
                  <span class="productName">KAHHVE TANIŞMA SETİ</span><br>
                  <span class="productMarka">KAHHVECOM</span><br>
                  <span class="productFiyat">124.99 TL</span>
              </div>
          </div>
      </div>
      
  </div>
</template>

<script>
export default {
    components:{

    },
    data() {
        return {
            imgSrc:[
                "https://kahhvecom.imgix.net/urunler/92_1604665685_IpH.jpg?h=750&ixlib=php-1.0.6&lossless=1&w=750&s=61c4196082c042619077e9fee599c617",
                "https://kahhvecom.imgix.net/urunler/112_1604665727_c2m.jpg?h=275&ixlib=php-1.0.6&lossless=1&w=275&s=20beb5e06c28a6b37e6ae756eb5da6ea",
                "https://kahhvecom.imgix.net/urunler/135_1604665766_R07.jpg?h=275&ixlib=php-1.0.6&lossless=1&w=275&s=23abe7b1b22609a44f08ccbaf1e9020b",
                "https://kahhvecom.imgix.net/urunler/696_1604665807_0v8.jpg?h=275&ixlib=php-1.0.6&lossless=1&w=275&s=1f253264a1767b8b59f03426a3a401a4",
                "https://kahhvecom.imgix.net/urunler/745_1604665822_D2J.jpg?h=275&ixlib=php-1.0.6&lossless=1&w=275&s=534b126d77f2b49e0c7db9d049eddd7b"
            ],
            imgIndex:0
        }
    }
}
    
</script>

<style>
    .centerArea{
        display: flex;
        flex-direction: row;
        width: 100%;
        height: 100%;
    }
    .productContent{
        display: flex;
        flex-direction: column;
        width: 100%;
    }
    .topArea{
        display: flex;
        flex-direction: row;
    }
    .imgArea{
        display: flex;
        flex-direction: column;
        width: 69%;
    }
    .productsList{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-between;
        width: 100%;
        background-color: white;
        padding-right: 20px;
        padding-left: 20px;
    }
    .productArea{
        background-color: #C65800;
        height: 250px;
        width: 250px;
        margin-bottom: 20px;
    }
    .productName{
        color: white;
        font-family: sans-serif;
        font-size: 18px;
        font-weight: bold;
    }
    .productMarka{
        color: gray;
        font-family: sans-serif;
        font-size: 18px;
    }
    .productFiyat{
        color: #603813;
        font-family: sans-serif;
        font-size: 18px;
        font-weight: bold;
    }
    .fullSizeImage{
        width: 250px;
        height: 250px;
        padding: 20px;
    }
    
</style>