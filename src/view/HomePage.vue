<style src="../styles/home.css"></style>

<template>
  <div>
    <Navigator/>
    <HeroSide/>
    <social/>
    <Feature_quote_left/>
    <Feature_Right/>
    <Feature_Left/>
    <Testimonial/>
    <CTA/>
    <Footer/>
  </div>
</template>

<script>
import Navigator from '../components/navigator/navigator.vue'
import HeroSide from '../components/HeroSide/HeroSide.vue'
import Feature_quote_left from '../components/feature_quote_left/feature_quoate_left.vue'
import Feature_Right from '../components/Feature_Quote_Right/Feature_Right.vue'
import Feature_Left from '../components/Feature_Quote_Left_Top/Feature_Left.vue'
import Testimonial from '../components/testimonial/testimonial.vue'
import Social from '../components/social-proof/Social.vue'
import CTA from '../components/cta/cta.vue'
import Footer from '../components/footer/footer.vue'


export default {
  name: 'HomePage',
  components: {
    Navigator,
    HeroSide,
    Feature_quote_left,
    Feature_Right,
    Feature_Left,
    Testimonial,
    Social,
    CTA,
    Footer
  }
}

</script>

