<template>
  <section class="container">
    <h1 class="title">Portfolio</h1>
    <p class="subtitle">Andrew Truex</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque ab voluptas eaque ipsam quibusdam quia esse nostrum amet voluptatibus in aut voluptates, id at, corporis blanditiis quisquam, reprehenderit suscipit sequi?</p>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Roboto', sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #36495d;
  letter-spacing: 1px;
}

.subtitle {
  font-family: 'Open Sans', sans-serif;
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
