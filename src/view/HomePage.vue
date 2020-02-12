
<style src="../styles/home.css"></style>
<template>
  <div class="hello">
    <Navigator/>
    <Footer/>
  </div>
</template>

<script>
import Navigator from '../components/navigator/navigator.vue'
import Footer from '../components/footer/footer.vue'


export default {
  name: 'HomePage',
  components: {
    Navigator,
    // eslint-disable-next-line vue/no-unused-components
    Footer
  }
}

</script>

