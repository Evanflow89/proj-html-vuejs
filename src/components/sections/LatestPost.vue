<template>
  <section>
    <div class="container latest_post text-center">
      <p class="p_head">Blog</p>
      <h2 class="head"><span>Latest</span> Posts</h2>
      <p class="p_content">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes <br />
        the upper surface.
      </p>
    </div>
    <div class="container posts pb-5">
      <div class="row d-flex">
        <div class="col-5 postcard_img d-flex align-items-end">
          <div class="container">
            <div class="row d-flex">
              <div class="col-12">
                <p>April 21, 2019 - By Paul</p>
                <div class="col-12 title">
                  <h5>Amazon Gets CCI nod to acquire 49% stake in</h5>
                </div>
              </div>
              <div class="container d-flex align-items-center">
                <div class="col-8">
                  <p>
                    When, while the lovely valley teems with vapour around meand
                    the meridian s...
                  </p>
                </div>
                <div
                  class="
                    col-4
                    d-flex
                    justify-content-end
                    read
                    align-items-center
                  "
                >
                  <button>Read More</button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-3 postcard p-4">
          <p class="pt-4">April 21, 2019 - By Paul</p>
          <div class="col-12 title pt-4">
            <h5>
              Clearing Corporation get SEBI nod to invest in overnight funds
            </h5>
          </div>
          <p class="pt-5">
            When, while the lovely valley teems with vapour around meand the
            meridian s...
          </p>
          <div class="read">
            <button class="mt-5">Read More</button>
          </div>
        </div>
        <div class="col-3 postcard p-4">
          <p class="pt-4">April 21, 2019 - By Paul</p>
          <div class="col-12 title pt-1">
            <h5>
              Shabnam Dhillion, wife of RSSB chief Gurinder Dhillion, passes
              away in London
            </h5>
          </div>
          <p class="pt-5">
            When, while the lovely valley teems with vapour around meand the
            meridian s...
          </p>
          <div class="read">
            <button class="mt-5">Read More</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "LatestPost",
};
</script>

<style lang="scss">
.latest_post {
  padding-top: 18.75rem;
  padding-bottom: 6.25rem;
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
.posts {
  p {
    color: var(--primary-color);
    font-size: 0.875rem;
  }
  .row {
    justify-content: center;
    gap: 1.5625rem;
  }
  .title h5 {
    color: var(--primary-color);
    padding: 0;
    margin: 0;
    font-size: 1rem;
    font-weight: 600;
  }
}
.postcard_img {
  width: 100%;
  background-image: url("../../assets/style/images/headway-537308-unsplash-1380x703.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  height: 21.875rem;
  border-radius: 30px;
  overflow: hidden;
}

.postcard {
  height: 21.875rem;
  border-radius: 30px;
  overflow: hidden;
  width: 100%;
  background-image: linear-gradient(#0b1953, #01012f);
}

.read button {
  color: black;
  padding: 6px 30px;
}
</style>