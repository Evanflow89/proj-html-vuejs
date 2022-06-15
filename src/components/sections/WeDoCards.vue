<template>
  <section class="wedo">
    <div class="container pt-5 pb-5">
      <div class="row">
        <ul class="text-center">
          <li class="col-12 col-md-6 col-lg-3">
            <img
              src="../../assets/style/images/Group-247.png"
              alt="Data Analysis"
            />
            <h4 class="pt-3 pb-4">Data Analysis</h4>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun strikes the upper
            </p>
          </li>
          <li class="col-12 col-md-6 col-lg-3">
            <img
              src="../../assets/style/images/Group-567.png"
              alt="Data Analysis"
            />
            <h4 class="pt-3 pb-4">SEO Optimization</h4>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun strikes the upper
            </p>
          </li>
          <li class="col-12 col-md-6 col-lg-3">
            <img
              src="../../assets/style/images/Group-538.png"
              alt="Security Data"
            />
            <h4 class="pt-3 pb-4">SEO Optimization</h4>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun strikes the upper
            </p>
          </li>
          <li class="col-12 col-md-6 col-lg-3">
            <img
              src="../../assets/style/images/Group-566.png"
              alt="Security Data"
            />
            <h4 class="pt-3 pb-4">Branding Strategy</h4>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun strikes the upper
            </p>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "WeDoCards",
};
</script>

<style lang="scss">
.wedo {
  ul li {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  ul li img {
    height: 6.25rem;
  }

  h4 {
    font-weight: 600;
  }
}
</style>