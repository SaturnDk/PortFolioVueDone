<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'


</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/imgs/SaturnLogo.png" width="125" height="125" margin="5" />

    <div class="wrapper">
      <nav id="desktop-nav">
        <!-- <div class="logo"> <img alt="Vue logo" class="logo" src="@/assets/imgs/SaturnLogo.png" width="125" height="125"/></div> -->
        <div>
            <ul class="nav-links">
                <RouterLink to="/">Home</RouterLink>
                <RouterLink to="/about">About</RouterLink>
                <RouterLink to="/Projects">Projects</RouterLink>
            </ul>
        </div>
    </nav>
    </div>
  </header>
  <RouterView />
</template>

<style scoped>

header {
  line-height: 1.5;
  max-height: 100vh;
  display: flex;
  justify-content: center;
  }

.logo {
  display: block;
  margin: auto 2rem;
  padding-left: 3rem;
  justify-self: flex-start;
}

nav {
  width: 100%;
  font-size: px;
  text-align: center;
  margin-top: 1rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
  text-decoration: underline;
  text-decoration-color: #1e82af;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;
    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
