<template>
    <div class="container-fluid">
    <section class="row">
      <div class="col-12">
        <p class="text-white d-flex align-items-end justify-content-center caveat-font fs-4" style="height: 10vh;">Showcasing some of my best work</p>
      </div>
      <div class="col-12">
        <h1 class="text-white text-center">Portfolio</h1>
      </div>
      <div class="col-12 d-flex justify-content-center text-center" >
        <section class="slide-divide" >
          <div class="dot"></div>
        </section>
      </div>
      <h2 class="text-white text-center mt-2"><a title="Link to Live Hosted Site" href="https://jasperdelightdonerighthomepage.work/#/" target="_blank"> Keeper </a> <a href="https://github.com/Jasperdelight/keepr" target="_blank"> <i title="GitHub Repo" class="mdi mdi-github"></i> </a></h2>
      <div class="col-4 my-3">
        <a href="https://i.imgur.com/QvivDFZ.jpg" target="_blank" alt="tower1"><img src="https://i.imgur.com/QvivDFZ.jpg" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4 my-3">
        <a href="https://i.imgur.com/OD7bxTM.png" target="_blank" alt="tower2"><img src="https://i.imgur.com/OD7bxTM.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4 my-3">
        <a href="https://i.imgur.com/VPSAN3i.png" target="_blank" alt="tower3"><img src="https://i.imgur.com/VPSAN3i.png" class="img-fluid" alt=""></a>
      </div>

      <h2 class="text-white text-center"><a href="https://codefitness-16iw.onrender.com/" title="Takes a while to load (due to OnRender Site hosted on)" target="_blank">CodeFitness</a> <a href="https://github.com/EwanStubblefield-Allen/CodeFitness" target="_blank"> <i title="GitHub Repo" class="mdi mdi-github"></i> </a></h2>
      <div class="col-4">
        <a href="https://i.imgur.com/ST1Xoci.png" target="_blank" alt="codeFitness1"><img src="https://i.imgur.com/ST1Xoci.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/XbbQIE7.png" target="_blank" alt="codeFitness2"><img src="https://i.imgur.com/XbbQIE7.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/NHdJKGV.png" target="_blank" alt="codeFitness3"><img src="https://i.imgur.com/NHdJKGV.png" class="img-fluid" alt=""></a>
      </div>
      <h2 class="text-white text-center"> <a href="https://tower-cqxd.onrender.com/#/" target="_blank" title="Takes a while to load (due to OnRender Site hosted on)"> Tower</a> <a href="https://github.com/Jasperdelight/towerCheckpoint" target="_blank"> <i title="GitHub Repo" class="mdi mdi-github"></i></a></h2>
      <div class="col-4">
        <a href="https://i.imgur.com/pw1WXl2.png" target="_blank" alt="tower1"><img src="https://i.imgur.com/pw1WXl2.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/iK3A0oZ.png" target="_blank" alt="tower2"><img src="https://i.imgur.com/iK3A0oZ.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/Um3N7cp.png" target="_blank" alt="tower3"><img src="https://i.imgur.com/Um3N7cp.png" class="img-fluid" alt=""></a>
      </div>
      <h2 class="text-white text-center">AllSpice <a href="https://github.com/Jasperdelight/allSpice" target="_blank"> <i title="GitHub Repo" class="mdi mdi-github"></i> </a></h2>
      <div class="col-4">
        <a href="https://i.imgur.com/G7HajPV.jpg" target="_blank" alt="codeFitness1"><img src="https://i.imgur.com/G7HajPV.jpg" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/yM3XdUq.png" target="_blank" alt="codeFitness2"><img src="https://i.imgur.com/yM3XdUq.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/8rScSHl.png" target="_blank" alt="codeFitness3"><img src="https://i.imgur.com/8rScSHl.png" class="img-fluid" alt=""></a>
      </div>

    </section>

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
        <section class="slide-divide1" >
          <div class="dot1"></div>
        </section>
      </div>
      <div class="col-12" style="height: 80vh;">
        <SocialsComponent/>
      </div>
    </section>
  </div>
  <div id="overlay-effect" class="animate-up"></div>

</template>


<script>
import { onMounted } from "vue";

export default {
  setup(){
    function       returnToTop(){
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
      }
    onMounted(()=>returnToTop())
    return {}
  }
}
</script>


<style lang="scss" scoped>
.app-image{
  justify-self: center;
  max-height: 10vh;
}
</style>