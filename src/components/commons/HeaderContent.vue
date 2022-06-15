<template>
  <div class="container header_content">
    <div class="row">
      <div class="col-6 d-flex flex-column justify-content-center">
        <span>Business Planning</span>
        <span class="thin">Digital Technology</span>
        <span class="pb-5">Modern Solution !</span>
        <p class="pb-5">
          When, while the lovely valley teems with vapour around <br />
          meand the meridian sun strikes the upper surface.
        </p>
        <div class="buttons d-flex">
          <button class="gradient-button-2">Try It Now</button>
          <button class="gradient-button-1">Explore More</button>
        </div>
      </div>
      <div class="col-6">
        <img
          class="img-fluid"
          src="../../assets/style/images/header.png"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderContent",
};
</script>

<style lang="scss">
.header_content {
  padding-bottom: 12.5rem;
}
.col-6 span {
  color: var(--primary-color);
  font-size: 3.375rem;
  font-weight: 600;
  line-height: 4.375rem;
}

.thin {
  font-weight: 400;
}

p {
  color: var(--parag-color);
  font-size: 1rem;
  line-height: 1.5rem;
}

.buttons {
  gap: 1.25rem;
}

.buttons button {
  font-size: 0.875rem;
  padding: 0.75rem 2.5rem;
}
</style>