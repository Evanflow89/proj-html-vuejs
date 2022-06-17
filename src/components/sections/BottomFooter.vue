<template>
  <div class="container">
    <div class="row bottom_footer d-flex justify-content-between">
      <div class="col-3">
        <p>&#169; 2020 Phlox. All Rights Reserved.</p>
      </div>
      <div class="col-4 d-flex social_icons">
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-linkedin-in"></i>
        <i class="fa-brands fa-facebook-f"></i>
        <i class="fa-brands fa-twitter"></i>
        <div class="arrow"></div>
        <div class="comic">
          <i class="fa-regular fa-comment"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BottomFooter",
};
</script>

<style lang="scss">
.bottom_footer {
  p {
    font-size: 0.875rem;
  }
  .social_icons {
    gap: 30px;
    justify-content: flex-end;
    color: var(--primary-color);
  }
}
</style>