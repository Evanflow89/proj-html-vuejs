<template>
  <section>
    <div class="container what_people text-center">
      <p class="p_head">Testimonial</p>
      <h2 class="head"><span>What</span> People Say</h2>
      <p class="p_content">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes <br />
        the upper surface.
      </p>
    </div>

    <!-- ############# CARDS SECTION ################# -->
    <div class="container people_cards">
      <div class="row">
        <div class="col-4">
          <div class="img_people d-flex justify-content-center">
            <img
              src="../../assets/style/images/szabo-viktor-1266895-unsplash-1024x1024.png"
              alt="User Image"
              class="mb-5"
            />
          </div>
          <div class="stars text-center pb-5">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-regular fa-star"></i>
            <i class="fa-regular fa-star"></i>
          </div>
          <p class="pb-3 text-center">
            When, while lovely valley teems with vapour around meand meridian
            sun strikes the upper impenetrable follage of my trees, and but a
            thousand.
          </p>
          <h6 class="text-center">Michkel Anegl</h6>
          <p class="text-center">Marketing Management</p>
        </div>
        <div class="col-4">
          <div class="img_people d-flex justify-content-center">
            <img
              src="../../assets/style/images/philipe-cavalcante-539505-unsplash-1024x1024.png"
              alt="User Image"
              class="mb-5"
            />
          </div>
          <div class="stars text-center pb-5">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-regular fa-star"></i>
            <i class="fa-regular fa-star"></i>
          </div>
          <p class="pb-3 text-center">
            When, while lovely valley teems with vapour around meand meridian
            sun strikes the upper impenetrable follage of my trees, and but a
            thousand.
          </p>
          <h6 class="text-center">Michkel Anegl</h6>
          <p class="text-center">Marketing Management</p>
        </div>
        <div class="col-4">
          <div class="img_people d-flex justify-content-center">
            <img
              src="../../assets/style/images/fabio-spinelli-695744-unsplash-1024x1024.png"
              alt="User Image"
              class="mb-5"
            />
          </div>
          <div class="stars text-center pb-5">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-regular fa-star"></i>
            <i class="fa-regular fa-star"></i>
          </div>
          <p class="pb-3 text-center">
            When, while lovely valley teems with vapour around meand meridian
            sun strikes the upper impenetrable follage of my trees, and but a
            thousand.
          </p>
          <h6 class="text-center">Michkel Anegl</h6>
          <p class="text-center">Marketing Management</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "WhatPeople",
};
</script>

<style lang="scss">
.what_people {
  padding-top: 9.375rem;
  padding-bottom: 9.375rem;
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
.people_cards {
  .img_people img {
    width: 7.5rem;
    border: 4px solid #b6256f;
    border-radius: 50%;
  }
  .fa-star {
    color: #b6256f;
  }
  p {
    font-size: 0.875rem;
    font-weight: 500;
  }
  h6 {
    font-weight: 600;
  }
}
</style>