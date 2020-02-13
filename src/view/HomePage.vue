<style src="../styles/home.css"></style>

<template>
  <div>
    <Navigator/>
    <Hero_side/>
  </div>
</template>

<script>
import Navigator from '../components/navigator/navigator.vue'
import Hero_side from '../components/hero_side/hero_side.vue'


export default {
  name: 'HomePage',
  components: {
    Navigator,
    Hero_side
  }
}

</script>

