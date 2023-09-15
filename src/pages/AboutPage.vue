  <template>
  <div class="container-fluid">
    <section class="row">
      <div class="col-12">
        <p class="text-white d-flex align-items-end justify-content-center" style="height: 10vh;">Get to know me</p>
      </div>
      <div class="col-12">
        <h1 class="text-white text-center">About Me</h1>
      </div>
      <div class="col-12 d-flex justify-content-center text-center mb-2" >
        <section class="slide-divide" >
          <div class="dot"></div>
        </section>
      </div>
      <div class="col-3"></div>
      <div class="col-md-3 col-12" >
        <img class="img-fluid"  src="https://i.imgur.com/eAxfvzE.jpg" alt="">
      </div>
      <div class="col-md-6 col-12">
        <section class="row">
          <div class="col-12 text-warning">Who Am I?</div>
          <div class="col-12 fs-3 text-white">- Full-Stack Software Developer -</div>
          <div class="col-12 text-white"> As someone who loves learning, I enjoy tackling problems and finding different solutions. I’m always eager to expand my knowledge, improve my skills, and approach familiar subjects from new angles. I welcome feedback and criticism as opportunities for personal growth. I’m dedicated to continual learning and self-improvement in any way possible. Recently, I discovered a passion for programming, and I find daily problem-solving incredibly fulfilling. My only regret is not starting sooner. The prospect of exploring various programming languages and acquiring new skills is both exciting and motivating. Also I’m a lifelong consumer of video games of all types as well as an avid bicyclist.</div>
          <div class="col-12 my-2" style="border-bottom: 5px solid red;"></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;">Name:</span> Jasper Delight</p></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;">Email:</span> jasperdelightt@gmail.com</p></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;">Age:</span> 30</p></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;">From:</span> Boise, Idaho</p></div>
        </section>
      </div>
    </section>
    <SocialsComponent/>
  </div>
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