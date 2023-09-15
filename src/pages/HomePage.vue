<template>
<div class="container-fluid bg-black">
  <section class="row" style="height: 60vh;">
    <div class="col-12 text-white fs-2 d-flex justify-content-center align-items-center"><h1>Jasper Delight</h1></div>
    <SocialsComponent/>
  </section>
  <div id="overlay-effect" class="animate-down"></div>
</div>

</template>

<script>
import SocialsComponent from "../components/SocialsComponent.vue";

export default {
    setup() {
      
        return {};
    },
    components: { SocialsComponent }
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
