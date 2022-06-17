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
          <li class="active"><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">Portfolio</a></li>
          <button class="gradient-button-1">Sign In</button>
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

.logo img {
  width: 6.25rem;
}

.active a {
  color: var(--text-var1);
  font-size: 0.75rem;
}

ul {
  list-style: none;
  display: flex;
  gap: 1.25rem;
}
ul li a {
  text-decoration: none;
  color: var(--primary-color);
  font-size: 0.75rem;
}

ul li a:hover {
  color: var(--text-var1);
}

button {
  margin-left: 20px;
}
</style>