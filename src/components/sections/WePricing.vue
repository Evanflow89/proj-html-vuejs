<template>
  <section class="price">
    <div class="container princing text-center">
      <p class="p_head">Price List</p>
      <h2 class="head"><span>Our</span> Pricing</h2>
      <p class="p_content">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes <br />
        the upper surface.
      </p>
    </div>

    <!-- ###############  PRICE CARDS ################# -->
    <div class="container price_cards">
      <div class="row">
        <div class="col-4">
          <div class="card text-center">
            <h3 class="pt-5">Designing</h3>
            <p>PROCESS</p>
            <h2 class="pt-3">40</h2>
            <p class="pb-4">Per Month</p>
            <p><span>Creative</span> Design Enabled</p>
            <p><span>Vibrant</span> Color Usage</p>
            <p><span>Eye</span> Catching Design</p>
            <p><span>Extreme</span> Typography</p>
            <p><span>Exceptional</span> Design</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss">
.price {
  padding-top: 5rem;
  background-image: linear-gradient(#0b1953, #01012f);
}
.princing {
  .p_head {
    color: var(--text-var1);
  }
  h2 {
    color: var(--primary-color);
  }
  .p_content {
    color: var(--primary-color);
  }
}
.price_cards {
  height: 25rem;
  .card {
    position: relative;
    width: 100%;
    height: 35rem;
    position: relative;
    bottom: -6.25rem;
    border-radius: 2.5rem;
    overflow: hidden;
    z-index: 3;
    h3 {
      font-weight: 600;
      font-size: 2.5rem;
    }
    h2 {
      font-weight: 600;
      font-size: 5rem;
    }

    p {
      font-size: 0.875rem;
    }
    span {
      font-size: 0.875rem;
    }
  }
  .card::after {
    position: absolute;
    content: "40";
    font-size: 300px;
    font-weight: 600;
    color: var(--text-lightgray);
    z-index: -1;
    top: -120px;
    left: 4.375rem;
    width: 100%;
    overflow: hidden;
  }
}
</style>