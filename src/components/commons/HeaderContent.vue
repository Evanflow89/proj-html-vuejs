<template>
  <div class="container">
    <div class="row">
      <div class="col-6 d-flex flex-column justify-content-center">
        <h1>Business Planning</h1>
        <p class="thin">Digital Technology</p>
        <p>Modern Solution !</p>
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
p {
  color: var(--primary-color);
  font-size: 3rem;
  font-weight: 600;
}

.thin {
  font-weight: 400;
}

.col-6 {
  line-height: 3.125rem;
}
</style>