<script>
import Appheader from './Appheader.vue';
import Appmain from './Appmain.vue';
import Appfooter from './Appfooter.vue';


export default {
  components:{
    Appheader,
    Appmain,
    Appfooter
  }
}
</script>
<template lang="">
  <div>
    <Appheader />
    <Appmain />
    <Appfooter />
  </div>
</template>
<style lang="scss">
  @use './styles/generals.scss'
</style>