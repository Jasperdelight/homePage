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
      <div class="col-3" >
        <img class="img-fluid"  src="https://images.unsplash.com/photo-1682686580452-37f1892ee5e8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHwxfHx8ZW58MHx8fHx8&auto=format&fit=crop&w=500&q=60" alt="">
      </div>
      <div class="col-6">
        <section class="row">
          <div class="col-12 text-warning">Who Am I?</div>
          <div class="col-12 fs-3 text-white">I'm Jasper Delight, a Full-Stack Software Developer</div>
          <div class="col-12 text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, id quos quas perspiciatis voluptate suscipit. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam aliquam sunt repudiandae magnam doloribus voluptates aut? Nemo, iusto quo vero unde impedit praesentium dignissimos est!</div>
          <div class="col-12 my-2" style="border-bottom: 5px solid red;"></div>
          <div class="col-6"><p class="text-white"><span style="font-weight: bold;">Name:</span> Jasper Delight</p></div>
          <div class="col-6"><p class="text-white"><span style="font-weight: bold;">Email:</span> jasperdelightt@gmail.com</p></div>
          <div class="col-6"><p class="text-white"><span style="font-weight: bold;">Age:</span> 30</p></div>
          <div class="col-6"><p class="text-white"><span style="font-weight: bold;">From:</span> Boise, Idaho</p></div>
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