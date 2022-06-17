<template>
  <footer>
    <top-footer />
    <bottom-footer />
  </footer>
</template>

<script>
import BottomFooter from "../sections/BottomFooter.vue";
import TopFooter from "../sections/TopFooter.vue";
export default {
  components: { TopFooter, BottomFooter },
  name: "BaseFooter",
};
</script>

<style lang="scss">
footer {
  background-image: linear-gradient(#0b1953, #01012f);
  padding-top: 12.5rem;
  color: var(--text-gray);
}
</style>