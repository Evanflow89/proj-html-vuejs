<template>
  <div class="container what_people text-center">
    <p class="p_head">Testimonial</p>
    <h2 class="head"><span>What</span> People Say</h2>
    <p class="p_content">
      When, while the lovely valley teems with vapour around meand the meridian
      sun strikes <br />
      the upper surface.
    </p>
  </div>
</template>

<script>
export default {
  name: "WhatPeople",
};
</script>

<style lang="scss">
.what_people {
  padding-top: 9.375rem;
  padding-bottom: 6.25rem;
  .p_head {
    color: var(--text-var1);
  }
  h2 {
    color: var(--text-black);
  }

  .p_content {
    color: var(--text-black);
  }
}
</style>