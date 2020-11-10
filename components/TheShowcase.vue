<template>
  <div>
      <div class="productsList">
          
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

}
</script>

<style>
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
        border-color: #C65800;
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
    
</style>