<template>
  <z-canvas :views="$options.components"></z-canvas>
</template>
<script>
import home from "/components/home";
import foo from "/components/foo";
export default {
  components: {
    home,
    foo
  },
  mounted() {
    this.$zircle.setView("home");
  }
};
</script>
<style>
</style>
