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
          <li v-for="(link, index) in links" :key="index">
            <a
              :class="link.active === true ? 'active' : false"
              :href="link.href"
              >{{ link.title }}</a
            >
          </li>
          <button class="gradient-button-1">Sign In</button>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderBar",
  data() {
    return {
      links: [
        {
          title: "About",
          href: "#",
          active: true,
        },
        {
          title: "Services",
          href: "#",
          active: false,
        },
        {
          title: "Blog",
          href: "#",
          active: false,
        },
        {
          title: "Contact",
          href: "#",
          active: false,
        },
        {
          title: "Portfolio",
          href: "#",
          active: false,
        },
      ],
    };
  },
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

.active {
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