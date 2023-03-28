<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
import Products from './components/Products.vue';
import TheFooter from './components/TheFooter.vue';

export default {
  components: {
    TheHeader, TheMain, Products, TheFooter
  }
}
</script>

<template>
  <div class="container">
    <TheHeader />
    <TheMain />
    <Products />
    <TheFooter />
  </div>
</template>

<style lang="scss">
@use "./styles/general.scss";
</style>
