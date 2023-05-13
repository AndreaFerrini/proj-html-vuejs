<script>

import HeaderComp from "./components/HeaderComp.Vue";
import NavHComp from "./components/NavHComp.vue"
import MainComp from "./components/MainComp.Vue";
import FooterComp from "./components/FooterComp.vue"

export default{
  name: "App",
  components: {
    HeaderComp,
    NavHComp,
    MainComp,
    FooterComp
  }
}

</script>

<template>
  <HeaderComp/>
  <NavHComp/>
  <MainComp/>
  <FooterComp/>


</template>

<style scoped>

</style>
