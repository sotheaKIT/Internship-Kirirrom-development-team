<style src="../styles/home.css"></style>

<template>
  <div>
    <Navigator/>
    <Hero_side/>
    <social/>
    <Feature_quote_left/>
    <CTA/>
    <Footer/>
  </div>
</template>

<script>
import Navigator from '../components/navigator/navigator.vue'
import Hero_side from '../components/hero_side/hero_side.vue'
import Feature_quote_left from '../components/feature_quote_left/feature_quoate_left.vue'
import Social from '../components/social-proof/Social.vue'
import CTA from '../components/cta/cta.vue'
import Footer from '../components/footer/footer.vue'


export default {
  name: 'HomePage',
  components: {
    Navigator,
    Hero_side,
    Feature_quote_left,
    Social,
    CTA,
    Footer
  }
}

</script>

