<template>
  <section>
    <div class="container latest_work">
      <p>Portfolio</p>
      <div class="row d-flex">
        <div class="col-6">
          <h2><span>latest</span> work</h2>
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
          <div class="work_card first d-flex p-4">
            <div class="card_text">Basket of Flower on table</div>
            <small>Branding Strategy</small>
          </div>
        </div>
        <div class="col-4">
          <div class="work_card second d-flex p-4">
            <div class="card_text">Purinky Products</div>
            <small>Digital Experience</small>
          </div>
        </div>
        <div class="col-4">
          <div class="work_card third d-flex p-4">
            <div class="card_text">Satisfy Poster</div>
            <small>Branding Strategy</small>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="slide d-flex justify-content-center pb-5">
            <div class="circle red"></div>
            <div class="circle gray"></div>
            <div class="circle gray"></div>
            <div class="circle gray"></div>
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
  padding-bottom: 6.25rem;
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

  .work_card:hover {
    background-image: linear-gradient(to right, #b7256e, #f8636b);
    color: var(--primary-color);
    small {
      color: #f9aab1;
    }
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
    position: absolute;
    width: 100%;
    height: 18.75rem;
    left: 0;
    bottom: 4.0625rem;
    border-radius: 50px;
    z-index: 1;
    overflow: hidden;
  }
  .work_card.first::after {
    background: url("../../assets/style/images/8wa60okr-1-790x576.jpg");
    background-size: 100%;
    background-repeat: no-repeat;
  }
  .work_card.second::after {
    background: url("../../assets/style/images/DRY-1-790x576.jpg");
    background-size: 100%;
    background-repeat: no-repeat;
  }
  .work_card.third::after {
    background: url("../../assets/style/images/a247b00b-3621-470f-b4b8-b3ac46f25907-1-790x576.jpg");
    background-size: 100%;
    background-repeat: no-repeat;
  }
}

.slide {
  gap: 0.625rem;
  .circle {
    height: 0.625rem;
    width: 0.625rem;
    background-color: var(--text-gray);
    border-radius: 50%;
    &.red {
      background-color: var(--text-var1);
    }
  }
}
</style>