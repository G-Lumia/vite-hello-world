<template lang="">
  <div>
    <AppHeader />
    <AppJumbo />
  </div>
</template>
<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
export default {
  name : 'App',
  components : {
    AppHeader,
    AppJumbo
  }
}
</script>
<style lang="scss" scoped>
  
</style>