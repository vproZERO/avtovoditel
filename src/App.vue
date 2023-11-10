<template>
  <div>
      <Header/>
      <Talim/>
      <Welcome/>
      <Price/>
  </div>
</template>
<script>
import Header from './components/header.vue'
import Talim from './components/talim.vue'
import Welcome from './components/welcome.vue'
import Price from './components/price.vue'
export default {
    components: {
      Header,
      Talim,
      Welcome,
      Price,
    }
}
</script>
<style lang="">
  
</style>