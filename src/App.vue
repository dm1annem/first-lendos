<template>
  <div id="app">
  <lend-wrapper/>
  </div>
</template>

<script>
import lendWrapper from './components/lend-wrapper'

export default {
  name: "App",
  components: {
    lendWrapper,
  }
};
</script>

<style>
  body {
    margin: 0;
  }
</style>
