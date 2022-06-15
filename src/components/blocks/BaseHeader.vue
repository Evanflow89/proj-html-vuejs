<template>
  <header>
    <header-bar />
    <header-content />
  </header>
</template>

<script>
import HeaderBar from "../commons/HeaderBar.vue";
import HeaderContent from "../commons/HeaderContent.vue";
export default {
  name: "BaseHeader",
  components: {
    HeaderBar,
    HeaderContent,
  },
};
</script>

<style lang="scss">
header {
  height: 100vh;
  background-image: linear-gradient(#0b1953, #01012f);
}
</style>