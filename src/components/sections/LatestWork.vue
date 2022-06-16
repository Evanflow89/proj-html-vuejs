<template>
  <section class="latest_work">
    <div class="container">
      <p>Portfolio</p>
      <div class="row d-flex">
        <div class="col-6">
          <h2><span>Latest</span> work</h2>
        </div>
        <div class="col-6 d-flex justify-content-end arrows">
          <div class="arrow">&#x2190;</div>
          <div class="arrow">&#x2192;</div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-3">
          <latest-card />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import LatestCard from "../commons/LatestCard.vue";
export default {
  components: { LatestCard },
  name: "LatestWork",
};
</script>

<style lang="scss">
.latest_work {
  padding-top: 6.25rem;
  p {
    color: var(--text-var1);
  }
  .arrows {
    gap: 0.9375rem;
  }

  .arrow {
    color: var(--text-var1);
    height: 2.5rem;
    width: 2.5rem;
    line-height: 2.5rem;
    text-align: center;
    border-radius: 50%;
    border: 1px solid var(--text-var1);
  }
}
</style>