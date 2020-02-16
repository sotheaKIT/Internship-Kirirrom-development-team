<style src="../styles/home.css"></style>

<template>
  <div>
    <Navigator/>
    <Hero_side/>
    <social/>
    <Footer/>
  </div>
</template>

<script>
import Navigator from '../components/navigator/navigator.vue'
import Hero_side from '../components/hero_side/hero_side.vue'
import Social from '../components/social-proof/Social.vue'
import Footer from '../components/footer/footer.vue'


export default {
  name: 'HomePage',
  components: {
    Navigator,
    Hero_side,
    Social,
    Footer
  }
}

</script>

