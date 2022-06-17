<template>
  <div class="container pt-5">
    <div class="row text-center what_we">
      <p class="redP">Our Services</p>
      <h2 class="pb-3"><span>What</span> We Do</h2>
      <p>When, while the lovely valley teems with vapour around meand the</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "WhatWeDo",
};
</script>

<style lang="scss">
main {
  p {
    color: var(--text-black2);
  }
  .redP {
    color: var(--text-var1);
  }

  span {
    font-weight: 700;
    font-size: 2.5rem;
  }

  h2 {
    font-size: 2.5rem;
    font-weight: 400;
  }
}
.what_we {
  padding-bottom: 6.25rem;
}
</style>