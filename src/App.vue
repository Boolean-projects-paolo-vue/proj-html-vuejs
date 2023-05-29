<script>
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooter from './components/AppFooter.vue';

  export default {
   
    components: { AppHeader, AppMain, AppFooter,}
};
</script>

<template>
  <div class="container_chess">
    <AppHeader />
    <AppMain />
    <appFooter />
  </div>
  
 

</template>

<style lang="scss">
  @import "../node_modules/bootstrap/scss/bootstrap";


  .container_chess{
    max-width: 1800px;
    height: 100%;
    margin:auto;
  }
</style>
