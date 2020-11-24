<template>
  <div id="app">
    <Button text="Go to link" link="http://fotiemconstant.github.io" />

    <hr />
    <VueButton text="fotiecode" link="http://fotiemconstant.github.io" />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Button from "./components/Vue-button.vue";
import VueButton from "vue-button-anotherone";

export default {
  name: "App",
  components: {
    Button,
    VueButton,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
