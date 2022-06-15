<template>
  <section class="grow_business">
    <div class="container grow_content">
      <div class="row">
        <div class="col-6 d-flex justify-content-center">
          <div class="img_back">
            <img src="../../assets/style/images/men-data.png" alt="" />
          </div>
        </div>
        <div class="col-6 d-flex flex-column justify-content-center">
          <span>Grow Your Business</span>
          <span class="thin">With Our Strategy</span>
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
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "GrowBusiness",
};
</script>

<style lang="scss">
.grow_business {
  background-image: linear-gradient(#0b1953, #01012f);

  .row {
    padding-top: 6.25rem;
  }

  p {
    color: var(--parag-color);
    font-size: 1rem;
    line-height: 1.5rem;
  }

  .col-6 img {
    max-width: 25rem;
    width: 100%;
    z-index: 10;
  }

  .img_back {
    position: relative;
    z-index: 1;
  }

  .img_back::after {
    content: "";
    background: url("../../assets/style/images/nemoodar.png");
    position: absolute;
    background-size: 100%;
    background-repeat: no-repeat;
    width: 400px;
    z-index: -1;
    bottom: 0;
    top: -40px;
    left: -50px;
  }
}

.grow_content {
  padding-bottom: 12.5rem;
}
.col-6 span {
  color: var(--primary-color);
  font-size: 3.375rem;
  font-weight: 600;
  line-height: 4.375rem;
}

span .thin {
  font-weight: 400;
}

.buttons {
  gap: 1.25rem;
}

.buttons button {
  font-size: 0.875rem;
  padding: 0.75rem 2.5rem;
}
</style>