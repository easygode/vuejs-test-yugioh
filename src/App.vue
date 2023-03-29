<script>
import HelloApp from './components/HelloApp.vue';
export default {
  name: 'App',
  components: {
    HelloApp
  }
}

</script>

<template>
<HelloApp></HelloApp>

<section>
  <select>
    <option value="">Prima Opzione</option>
  </select>
</section>

</template>

<style lang="scss">
@use './assets/scss/main.scss' as *;
</style>