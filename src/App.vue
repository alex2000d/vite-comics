<script>
import Appheader from './Appheader.vue';
import Appmain from './Appmain.vue';


export default {
  components:{
    Appheader,
    Appmain
  }
}
</script>
<template lang="">
  <div>
    <Appheader />
    <Appmain />
  </div>
</template>
<style lang="scss">
  @use './styles/generals.scss'
</style>