<script>

import HeaderComp from "./components/HeaderComp.Vue";
import NavHComp from "./components/NavHComp.vue"
import MainComp from "./components/MainComp.Vue";
import MainPosts from "./components/MainPosts.vue";
import BannerButton from "./components/BannerButton.vue";
import LastPost from "./components/LastPost.vue";
import MainBottom from "./components/MainBottom.vue";
import FooterComp from "./components/FooterComp.vue"

export default{
  name: "App",
  components: {
    HeaderComp,
    NavHComp,
    MainComp,
    MainPosts,
    BannerButton,
    LastPost,
    MainBottom,
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
  <LastPost/>
  <MainBottom/>
  <FooterComp/>


</template>

<style scoped>

</style>
