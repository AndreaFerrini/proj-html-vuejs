<script>

import HeaderComp from "./components/HeaderComp.Vue";
import NavHComp from "./components/NavHComp.vue"
import MainComp from "./components/MainComp.Vue";
import MainPosts from "./components/MainPosts.vue";
import BannerButton from "./components/BannerButton.vue";
import FooterComp from "./components/FooterComp.vue"

export default{
  name: "App",
  components: {
    HeaderComp,
    NavHComp,
    MainComp,
    MainPosts,
    BannerButton,
    FooterComp
  }
}

</script>

<template>
  <HeaderComp/>
  <NavHComp/>
  <MainComp/>
  <MainPosts/>
  <BannerButton/>
  <FooterComp/>


</template>

<style scoped>

</style>
