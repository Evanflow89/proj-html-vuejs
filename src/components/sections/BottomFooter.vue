<template>
  <div class="container">
    <div class="row bottom_footer d-flex justify-content-between">
      <div class="col-3 d-flex align-items-center">
        <p>&#169; 2020 Phlox. All Rights Reserved.</p>
      </div>
      <div class="col-4 d-flex social_icons align-items-center mr-5">
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-linkedin-in"></i>
        <i class="fa-brands fa-facebook-f"></i>
        <i class="fa-brands fa-twitter"></i>
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
  padding-bottom: 1.25rem;
  p {
    font-size: 0.875rem;
  }
  .social_icons {
    gap: 30px;
    justify-content: flex-end;
    color: var(--primary-color);
    position: relative;
  }

  .social_icons::after {
    content: "\2191";
    background-color: var(--primary-color);
    color: black;
    width: 1.5625rem;
    height: 1.5625rem;
    text-align: center;
    line-height: 1.5625rem;
    border-radius: 50%;
    position: absolute;
    top: -20px;
    right: -30px;
  }
}
.comic {
  height: 3.125rem;
  font-size: 1rem;
  width: 3.125rem;
  line-height: 3.125rem;
  text-align: center;
  border-radius: 50%;
  background-color: var(--parag-color);
  position: absolute;
  top: -0.3125rem;
  right: -90px;
}
</style>