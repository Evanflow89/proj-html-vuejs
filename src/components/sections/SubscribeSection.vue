<template>
  <section>
    <div class="container">
      <div class="row subscribe_section p-5">
        <div class="col-7 d-flex">
          <h2>We Offer Awesome Services</h2>
          <p>
            When, while lovely valley teems with vapour around meand meridian
            sun strikes the upper surface.
          </p>
        </div>
        <div class="col-5 d-flex">
          <input type="email" placeholder="Enter Your Email Address" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SubscribeSection",
};
</script>

<style lang="scss">
.subscribe_section {
  border-radius: 30px;
  margin-bottom: -100px;
  position: relative;
  background-image: linear-gradient(to right, #b7256e, #f8636b);
  h2 {
    font-weight: 700;
    color: var(--primary-color);
  }
  p {
    color: var(--primary-color);
    font-size: 0.875rem;
  }
  .col-7 {
    padding: 1.875rem 0;
    flex-direction: column;
    justify-content: center;
  }

  .col-5 {
    align-items: center;
    justify-content: flex-end;
    input {
      width: 25rem;
      border-radius: 30px;
      border: none;
      padding: 15px;
      font-size: 0.875rem;
    }
  }
}
</style>