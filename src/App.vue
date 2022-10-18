<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-dark">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/pierre">Pierre</RouterLink>
    <RouterLink to="/lisa">Lisa</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav>
  <div class="container">
    <RouterView />
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

.blank-header {
  /* min-width: 1200px; */
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}

nav a.router-link-exact-active {
  color: var(--color-text-dark);
  border-radius: 1em;
  color: rgb(255, 255, 255);
  background-color: hsla(0, 0%, 95%, 0.2);
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
    /* display: flex; */
    /* place-items: center; */
    /* padding-right: calc(var(--section-gap) / 2); */
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
