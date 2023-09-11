<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-black px-3">
    <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
      <div class="d-flex flex-column align-items-center">
        <h1>Home</h1>
      </div>
    </router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText"
      aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto">
        <li>
          <router-link :to="{ name: 'About' }" class="btn text-white selectable">
            About
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Resume' }" class="btn text-white selectable">
            Resume
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Portfolio' }" class="btn text-white selectable">
            Portfolio
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Contact' }" class="btn text-white selectable">
            Contact
          </router-link>
        </li>
      </ul>
      <!-- LOGIN COMPONENT HERE -->
    </div>
  </nav>
</template>

<script>

export default {
  setup() {
    return {}
  }
}
</script>

<style scoped>
a:hover {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-danger);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}
</style>
