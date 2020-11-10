<template>
  <div>
    <UnregisteredUserNavbar/>
    <Nuxt />
    <TheFooter/>
    
  </div>
</template>

<script>
import UnregisteredUserNavbar from "../components/UnregisteredUserNavbar"
import TheFooter from "../components/TheFooter"


export default {
  UnregisteredUserNavbar,
  TheFooter  
}
</script>

<style>

</style>
