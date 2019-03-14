<template>
  <section class="container">
    <div>
      <h1 class="title">Portfolio</h1>
      <br>
      <br>
      <logo/>

      <p class="subtitle">Andrew Truex</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque ab voluptas eaque ipsam quibusdam quia esse nostrum amet voluptatibus in aut voluptates, id at, corporis blanditiis quisquam, reprehenderit suscipit sequi?</p>
    </div>
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
h1.title {
  color: #f46036;
}
p,
p.subtitle {
  /* color: #192b33; */
  color: #ffffff;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #192b33;
  color: #f46036;
  margin-right: 0px;
  margin-left: 0px;
  max-width: max-content;
  width: auto;
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
