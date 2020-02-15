<style src="../styles/home.css"></style>

<template>
  <div>
    <Navigator/>
    <social/>
    <Footer/>
  </div>
</template>

<script>
import Navigator from '../components/navigator/navigator.vue'
import Social from '../components/social-proof/Social.vue'
import Footer from '../components/footer/footer.vue'


export default {
  name: 'HomePage',
  components: {
    Navigator,
    Social,
    Footer
  }
}

</script>

