<template>
  <section>
    <div class="container latest_post text-center">
      <p class="p_head">Blog</p>
      <h2 class="head"><span>Latest</span> Posts</h2>
      <p class="p_content">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes <br />
        the upper surface.
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "LatestPost",
};
</script>

<style lang="scss">
.latest_post {
  padding-top: 18.75rem;
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