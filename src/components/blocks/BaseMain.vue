<template>
  <main>
    <what-we-do />
    <WeDoCards />
    <wedoButton />
    <grow-business />
    <latest-work />
    <WePricing />
    <latest-post />
    <what-people />
    <subscribe-section />
  </main>
</template>

<script>
import WhatWeDo from "../sections/WhatWeDo.vue";
import WeDoCards from "../sections/WeDoCards.vue";
import WedoButton from "../commons/wedoButton.vue";
import GrowBusiness from "../sections/GrowBusiness.vue";
import LatestWork from "../sections/LatestWork.vue";
import WePricing from "../sections/WePricing.vue";
import LatestPost from "../sections/LatestPost.vue";
import WhatPeople from "../sections/WhatPeople.vue";
import SubscribeSection from "../sections/SubscribeSection.vue";

export default {
  name: "BaseMain",
  components: {
    WhatWeDo,
    WeDoCards,
    WedoButton,
    GrowBusiness,
    LatestWork,
    WePricing,
    LatestPost,
    WhatPeople,
    SubscribeSection,
  },
};
</script>,


<style lang="scss">
main {
  color: var(--text-black);
}
</style>