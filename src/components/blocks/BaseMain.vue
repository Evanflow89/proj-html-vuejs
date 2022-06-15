<template>
  <main>
    <what-we-do />
    <WeDoCards />
  </main>
</template>

<script>
import WhatWeDo from "../sections/WhatWeDo.vue";
import WeDoCards from "../sections/WeDoCards.vue";
export default {
  name: "BaseMain",
  components: { WhatWeDo, WeDoCards },
};
</script>

<style lang="scss">
main {
  color: var(--text-black);
}
</style>