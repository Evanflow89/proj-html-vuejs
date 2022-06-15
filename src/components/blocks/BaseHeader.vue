<template>
  <header>
    <header-bar />
  </header>
</template>

<script>
import HeaderBar from "../commons/HeaderBar.vue";
export default {
  name: "BaseHeader",
  components: {
    HeaderBar,
  },
};
</script>

<style lang="scss">
header {
  height: 75vh;
  background-image: linear-gradient(#0b1953, #01012f);
}
</style>