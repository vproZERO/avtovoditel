<template>
  <div>
      <Header/>
      <Talim/>
      <Welcome/>
      <Price/>
      <Picture/>
      <Maps/>
  </div>
</template>
<script>
import Header from './components/header.vue'
import Talim from './components/talim.vue'
import Welcome from './components/welcome.vue'
import Price from './components/price.vue'
import Picture from './components/picture.vue'
import Maps from './components/maps.vue'
export default {
    components: {
      Header,
      Talim,
      Welcome,
      Price,
      Picture,
      Maps,
    }
}
</script>
<style lang="">
  
</style>