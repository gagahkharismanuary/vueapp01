<template>
  <div id="app">
    <!-- <HelloWorld/> -->
    <listCard/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import listCard from './components/listCard';


export default {
  name: 'App',
  components: {
    HelloWorld,
    listCard,
  },
};
</script>

<style lang="scss">
  @import "../styles/main.scss"
</style>
