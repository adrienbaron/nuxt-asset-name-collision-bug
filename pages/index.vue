<template>
  <section class="container">
    <div>
      <h1 class="title">
        asset-name-collision-bug
      </h1>
      <div class="links">
        <h2>Should be big:</h2>
        <img src="~/assets/big/archer.png" alt="">
        <h2>Should be small:</h2>
        <img src="~/assets/small/archer.png" alt="">
      </div>
    </div>
  </section>
</template>

<script>
export default {
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
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
</style>

