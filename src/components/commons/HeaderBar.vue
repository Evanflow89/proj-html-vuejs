<template>
  <div class="container">
    <div class="head-bar d-flex p-2">
      <div class="logo">
        <img
          src="../../assets/style/images/white-logo-2.png"
          alt="Phlox Logo"
        />
      </div>
      <nav class="navsection">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">Portfolio</a></li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderBar",
};
</script>

<style lang="scss">
.head-bar {
  justify-content: space-between;
  align-items: center;
}
ul {
  list-style: none;
  display: flex;
  gap: 0.625rem;
}
ul li a {
  text-decoration: none;
  color: var(--primary-color);
}
</style>