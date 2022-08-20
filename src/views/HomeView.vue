<template>
  <div class="home">
    <nav-web />
    <first-banner-home />
    <second-banner />
    <content-banner />
    <vue-footer />
  </div>
</template>

<script>
import ContentBanner from '../components/ContentBanner.vue'
import FirstBannerHome from '../components/FirstBannerHome.vue'
import NavWeb from '../components/NavWeb.vue'
import SecondBanner from '../components/SecondBanner.vue'
import VueFooter from '../components/VueFooter.vue'



export default {
  name: 'HomeView',
  components: {
    FirstBannerHome,
    NavWeb,
    SecondBanner,
    ContentBanner,
    VueFooter
    }
}
</script>

<style scoped>
    
</style>
