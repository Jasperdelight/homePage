<template>
    <div class="container-fluid">
    <section class="row">
      <div class="col-12">
        <p class="text-white d-flex align-items-end justify-content-center caveat-font fs-4" style="height: 10vh;">Feel free to contact me anytime</p>
      </div>
      <div class="col-12">
        <a class="" href="https://share.hsforms.com/18SBh45f0Qfu3RSN3BH2x_wq43x5" target="_blank">
          <h1 class=" text-center">Get in Touch <i title="Send me and Email!" class="mdi mdi-email  fs-2" ></i></h1>
    </a>
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
import { onMounted } from "vue";
import SocialsComponent from "../components/SocialsComponent.vue";

export default {
    setup() {
      function       returnToTop(){
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
      }
    onMounted(()=>returnToTop())
        return {};
    },
    components: { SocialsComponent }
}
</script>


<style lang="scss" scoped>

</style>