<template>
  <section class="container">
    <div>
      <h1 class="title">About</h1>
      <nuxt/>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  text-align: center;
  /* font-family: Open Sans, sans-serif; */
}
.title {
  font-family: Open Sans, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #36495d;
  letter-spacing: 1px;
}
</style>
