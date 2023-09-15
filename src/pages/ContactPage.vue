<template>
    <div class="container-fluid">
    <section class="row">
      <div class="col-12">
        <p class="text-white d-flex align-items-end justify-content-center" style="height: 10vh;">Feel free to contact me anytime</p>
      </div>
      <div class="col-12">
        
        <h1 class="text-white text-center">Get in Touch <a class="" href="https://share.hsforms.com/18SBh45f0Qfu3RSN3BH2x_wq43x5" target="_blank"><i title="Send me and Email!" class="mdi mdi-email  fs-2" style="color: red
        ;"></i></a></h1>
      </div>
      <div class="col-12 d-flex justify-content-center text-center" >
        <section class="slide-divide" >
          <div class="dot"></div>
        </section>
      </div>
    </section>
  </div>
  <SocialsComponent/>
  <div id="overlay-effect" class="animate-up"></div>

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


<style lang="scss" scoped>

</style>