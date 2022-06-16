<template>
  <main>
    <what-we-do />
    <WeDoCards />
    <wedoButton />
    <grow-business />
    <latest-work />
  </main>
</template>

<script>
import WhatWeDo from "../sections/WhatWeDo.vue";
import WeDoCards from "../sections/WeDoCards.vue";
import WedoButton from "../commons/wedoButton.vue";
import GrowBusiness from "../sections/GrowBusiness.vue";
import LatestWork from "../sections/LatestWork.vue";

export default {
  name: "BaseMain",
  components: { WhatWeDo, WeDoCards, WedoButton, GrowBusiness, LatestWork },
};
</script>,


<style lang="scss">
main {
  color: var(--text-black);
}
</style>