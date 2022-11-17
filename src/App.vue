<template>
  <Hud ref="hud"/>
</template>

<script>
import Hud from './components/HUD.vue'

export default {
  name: 'App',
  components: {
    Hud
  },
  mounted () {
    //set global entry point for ragemp
    //global.gangwarhud = this.$refs.hud
  }
}
</script>