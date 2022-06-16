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

    <!-- ############# CARDS ############### -->
    <div class="container pb-5">
      <div class="row latest_cards">
        <div class="col-4">
          <div class="work_card d-flex p-4">
            <div class="card_text">Basket of Flower on table</div>
            <small>Branding Strategy</small>
          </div>
        </div>
        <div class="col-4">
          <div class="work_card d-flex p-4">
            <div class="card_text">Basket of Flower on table</div>
            <small>Branding Strategy</small>
          </div>
        </div>
        <div class="col-4">
          <div class="work_card d-flex p-4">
            <div class="card_text">Basket of Flower on table</div>
            <small>Branding Strategy</small>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
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

.latest_cards {
  .work_card {
    background-color: white;
    height: 365px;
    width: 100%;
    border-radius: 50px;
    justify-content: space-between;
    align-items: flex-end;
    position: relative;
    box-shadow: 2px 2px 5px gray;
  }

  .card_text {
    font-weight: 700;
    font-size: 0.875rem;
  }

  small {
    font-weight: 300;
    color: var(--text-gray);
  }

  .work_card::after {
    content: "";
    background: url("../../assets/style/images/8wa60okr-1-790x576.jpg");
    position: absolute;
    background-size: 100%;
    background-repeat: no-repeat;
    width: 100%;
    height: 18.75rem;
    left: 0;
    bottom: 4rem;
    border-radius: 50px;
    z-index: 1;
    overflow: hidden;
  }
}
</style>