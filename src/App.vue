<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ClassComponentExample/>
    <ComplexClassComponentExample/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import ClassComponentExample from './components/ClassComponentExample.vue';
import ComplexClassComponentExample from './components/ComplexClassComponentExample.vue';

export default {
  name: 'app',
  components: {
    HelloWorld,
    ClassComponentExample,
    ComplexClassComponentExample
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
