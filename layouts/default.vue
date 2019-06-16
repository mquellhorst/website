<template>
  <div>
    <navigation />
    <nuxt />
    <site-footer />
  </div>
</template>

<script>
import SiteFooter from '@/components/SiteFooter'
import Navigation from '@/components/Navigation'
export default {
  components: {
    SiteFooter,
    Navigation
  }
}
</script>

<style lang="sass">
@import "../assets/global.sass"
</style>
