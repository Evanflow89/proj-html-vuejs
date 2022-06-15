<template>
  <main>
    <what-we-do />
    <WeDoCards />
    <wedoButton />
    <grow-business />
  </main>
</template>

<script>
import WhatWeDo from "../sections/WhatWeDo.vue";
import WeDoCards from "../sections/WeDoCards.vue";
import WedoButton from "../commons/wedoButton.vue";
import GrowBusiness from "../sections/GrowBusiness.vue";

export default {
  name: "BaseMain",
  components: { WhatWeDo, WeDoCards, WedoButton, GrowBusiness },
};
</script>,
    WedoButton

<style lang="scss">
main {
  color: var(--text-black);
}
</style>