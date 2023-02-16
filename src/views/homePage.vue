<template>
    <div>
      <nav-bar></nav-bar>
      <banner></banner>
    </div>
</template>

<script>
import navBar from '@/components/navBar.vue';
import banner from '@/components/banner.vue'

export default {
  name: 'home-page',
  components: {
    navBar,
    banner
  }
}
</script>

<style scoped>
</style>
