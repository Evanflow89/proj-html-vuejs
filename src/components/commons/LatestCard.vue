<template>
  <section class="latest_cards">
    <div class="work_card d-flex p-4">
      <div class="card_text">Purity Product</div>
      <small>Digital Experience</small>
    </div>
  </section>
</template>

<script>
export default {
  name: "LatestCard",
};
</script>

<style lang="scss">
.latest_cards {
  .work_card {
    background-color: white;
    height: 18.75rem;
    width: 100%;
    border-radius: 20px;
    justify-content: space-between;
    align-items: flex-end;
    position: relative;
    box-shadow: 2px 2px 10px gray;
  }

  .card_text {
    font-weight: 600;
  }

  small {
    font-weight: 300;
    color: var(--text-gray);
  }

  .work_card::after {
    content: "";
    background: url("../../assets/style/images/DRY-1-790x576.jpg");
    position: absolute;
    background-size: 100%;
    background-repeat: no-repeat;
    width: 100%;
    height: 18.75rem;
    left: 0;
    bottom: -0px;
    border-radius: 20px;
    z-index: 1;
    overflow: hidden;
  }
}
</style>