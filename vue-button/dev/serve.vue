<script>
import Vue from "vue";
import VueButton from "@/vue-button.vue";

export default Vue.extend({
  name: "ServeDev",
  components: {
    VueButton,
  },
});
</script>

<template>
  <div id="app">
    <vue-button text="Please sub" link="http://fotiemconstant.github.io" />
  </div>
</template>
