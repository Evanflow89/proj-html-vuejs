<template>
  <section>
    <div class="container">
      <div class="row top_footer">
        <div class="col-3">
          <div class="logo pb-5">
            <img
              src="../../assets/style/images/white-logo-2.png"
              alt="logo image"
            />
          </div>
          <p>
            When, while lovely valley teems vapour around meand meridian sun
            strikes the upper impenetrable
          </p>
        </div>
        <div class="col-3">
          <h5>Quick Links</h5>
          <ul class="d-flex flex-column">
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Blog</a></li>
          </ul>
        </div>
        <div class="col-3">
          <h5>Resources</h5>
          <ul class="d-flex flex-column align-items-end">
            <li><a href="#">Art Design</a></li>
            <li><a href="#">Computer</a></li>
            <li><a href="#">IT News</a></li>
            <li><a href="#">Networking</a></li>
            <li><a href="#">Web Security</a></li>
          </ul>
        </div>
        <div class="col-3">
          <h5>Contact Us</h5>
          <div class="address">
            <p>
              <span>Address:</span> Patricia C. Amedee 4401 Waldeck <br />
              Street Grapevine Nashville, Tx 76051
            </p>
          </div>
          <div class="contacts">
            <p><span>Phone:</span> 099 (0) 101 0000 888</p>
            <p><span>Email:</span> info@yourdomain.com</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TopFooter",
};
</script>

<style lang="scss">
.top_footer {
  ul {
    padding: 0;
    margin: 0;
  }
  .logo img {
    width: 9.375rem;
  }
  p {
    font-size: 0.875rem;
  }
}
</style>