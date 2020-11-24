<template>
  <a :href="link"
    ><button>{{ text }}</button></a
  >
</template>

<script>
export default {
  props: {
    text: String,
    link: String,
  },
};
</script>