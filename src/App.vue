<template>
  <HelloWorld msg="my app" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>

<style>
@import './assets/stylesheets/reset.css';
* {
  box-sizing: border-box;
}
</style>
