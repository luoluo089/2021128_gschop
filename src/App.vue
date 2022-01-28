<template>
  <div>
    <router-view/>
    <FooterGuide v-if="$route.meta.showFooter"/>
  </div>
</template>

<script>
import FooterGuide from './components/FooterGuide'
export default {
  components: {FooterGuide}
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">

</style>
