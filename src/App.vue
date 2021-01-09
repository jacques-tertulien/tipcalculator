<template>
  <div>
    <TipCalculatour />
  </div>
</template>

<script>
import TipCalculatour from '@/components/TipCalculatour.vue';

export default {
  name: 'App',
  components: {
    TipCalculatour,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
