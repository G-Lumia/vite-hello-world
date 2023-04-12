<template lang="">
  <div>
    <AppTitle />
    <AppJumbo />
  </div>
</template>
<script>
import AppTitle from './components/AppTitle.vue';
import AppJumbo from './components/AppJumbo.vue';
export default {
  name : 'App',
  components : {
    AppTitle,
    AppJumbo
  }
}
</script>
<style lang="scss" scoped>
  
</style>