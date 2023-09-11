<template>
<div class="container-fluid bg-black">
  <section class="row" style="height: 70vh;">
    <div class="col-12 text-white fs-2 d-flex justify-content-center align-items-center">Jasper Delight</div>
  </section>
</div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: 50vw;

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
