<script>
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooter from './components/AppFooter.vue';

  export default {
    AppHeader,
    AppMain,
    AppFooter,
    components: { AppHeader, AppFooter }
};
</script>

<template>
  <div>
    <AppHeader />
    <AppMain />
    <appFooter />
  </div>
  
 

</template>

<style lang="scss" scoped>
  @import "../node_modules/bootstrap/scss/bootstrap";
</style>
