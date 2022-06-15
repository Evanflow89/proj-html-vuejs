<template>
  <main>
    <what-we-do />
  </main>
</template>

<script>
import WhatWeDo from "../sections/WhatWeDo.vue";
export default {
  name: "BaseMain",
  components: { WhatWeDo },
};
</script>

<style lang="scss">
main {
  color: var(--text-black);
}
</style>