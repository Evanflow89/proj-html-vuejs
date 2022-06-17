<template>
  <section class="wedo">
    <div class="container pt-5 pb-5">
      <div class="row">
        <ul class="text-center">
          <li class="col-12 col-md-6 col-lg-3 p-4">
            <img
              src="../../assets/style/images/Group-247.png"
              alt="Data Analysis"
            />
            <h4>Data Analysis</h4>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun strikes the upper
            </p>
          </li>
          <li class="col-12 col-md-6 col-lg-3 p-4">
            <img
              src="../../assets/style/images/Group-567.png"
              alt="Data Analysis"
            />
            <h4>SEO Optimization</h4>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun strikes the upper
            </p>
          </li>
          <li class="col-12 col-md-6 col-lg-3 p-4">
            <img
              src="../../assets/style/images/Group-538.png"
              alt="Security Data"
            />
            <h4>SEO Optimization</h4>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun strikes the upper
            </p>
          </li>
          <li class="col-12 col-md-6 col-lg-3 p-4">
            <img
              src="../../assets/style/images/Group-566.png"
              alt="Security Data"
            />
            <h4>Branding Strategy</h4>
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
    border-radius: 1.875rem;
    position: relative;
  }

  ul li img {
    height: 11.25rem;
    border-radius: 1.875rem;
    position: absolute;
    bottom: 15.625rem;
  }

  ul li:hover {
    background-image: linear-gradient(#0b1953, #01012f);
    color: var(--primary-color);
    p {
      color: var(--primary-color);
    }
    img {
      background-color: var(--primary-color);
      box-shadow: 1px 1px 2px black;
    }
  }

  h4 {
    font-weight: 600;
    padding-top: 6.25rem;
    padding-bottom: 1.875rem;
  }
  p {
    padding-bottom: 2.5rem;
  }
}
</style>