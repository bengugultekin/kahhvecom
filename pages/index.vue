<template>
  <div class="mainContainer">
    <TheSlider/>
    <h2 class="coksatan">ÇOK SATAN TANIŞMA SETLERİ</h2>
    <TheShowcase/>

  </div>
</template>

<script>
import TheSlider from "../components/TheSlider"
import TheShowcase from "../components/TheShowcase"
export default {
  TheSlider,
  TheShowcase
}
</script>

<style>
  .mainContainer{
    display: flex;
    flex-direction: column;
    width: 100%;
    align-items: center;
  }
  .coksatan{
        color: #C65800;
        font-family: sans-serif;
        font-weight: bold;
    }
</style>
