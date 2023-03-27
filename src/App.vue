<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
import TheFooter from './components/TheFooter.vue';

export default {
  components: {
    TheHeader, TheMain, TheFooter
  }
}
</script>

<template>
  <div class="container">
    <TheHeader />
    <TheMain />
    <TheFooter />
  </div>
</template>

<style >
.container {
  max-width: 60%;
  margin: auto;
}
</style>
