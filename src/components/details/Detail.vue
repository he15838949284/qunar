<template>
  <div>
      <detail-banner></detail-banner>
      <detail-header></detail-header>
      <div style="height:2000px"></div>
  </div>
</template>

<script>
import DetailBanner from './page/Banner'
import DetailHeader from './page/Header'
export default {
  components:{
    DetailBanner,
    DetailHeader
  },
  activated() {
    document.documentElement.scrollTop=0;
  },
}
</script>

<style scoped>

</style>