<template>

<div class="container-fluid bg-black">
  <section class="row" style="height: 30vh;">
    <div class="col-12 text-white fs-2 d-flex justify-content-center align-items-end"><h1>Jasper Delight</h1> </div>
      <p class="text-center text-white my-0 lobster-font">Developer & Designer</p>
      <SocialsComponent/>

  </section>

  <div id="overlay-effect" class="animate-down"></div>

    <section class="row">
      <div class="col-12">
        <p class="text-white d-flex align-items-end justify-content-center caveat-font fs-4" style="height: 10vh;">Get to know me</p>
      </div>
      <div class="col-12">
        <h1 class="text-white text-center">About Me</h1>
      </div>
      <div class="col-12 d-flex justify-content-center text-center mb-2" >
        <section class="slide-divide" >
          <div class="dot"></div>
        </section>
      </div>
      <div class="col-2"></div>
      <div class="col-md-3 col-12" >
        <img class="img-fluid rounded"  src="https://i.imgur.com/eAxfvzE.jpg" alt="">
      </div>
      <div class="col-md-6 col-12">
        <section class="row">
          <div class="col-12 text-warning">Who Am I?</div>
          <div class="col-12 fs-3 text-white">- Full-Stack Software Developer -</div>
          <div class="col-md-10 col-12 text-white me-2"> As someone who loves learning, I enjoy tackling problems and finding different solutions. I’m always eager to expand my knowledge, improve my skills, and approach familiar subjects from new angles. I welcome feedback and criticism as opportunities for personal growth. I’m dedicated to continual learning and self-improvement in any way possible. Recently, I discovered a passion for programming, and I find daily problem-solving incredibly fulfilling. My only regret is not starting sooner. The prospect of exploring various programming languages and acquiring new skills is both exciting and motivating. I’m also a lifelong consumer of video games of all types as well as an avid bicyclist.</div>
          <div class="col-md-10 col-12 my-2" style="border-bottom: 5px solid red;"></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;">Name:</span> Jasper Delight</p></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;">Email:</span> jasperdelightt@gmail.com</p></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;"></span></p></div>
          <div class="col-md-6 col-12"><p class="text-white"><span style="font-weight: bold;">From:</span> Boise, Idaho</p></div>
        </section>
      </div>
    </section>

    <section class="row">
      <div class="col-12">
        <p class="text-white d-flex align-items-end justify-content-center caveat-font fs-4" style="height: 10vh;">Check out my Resume</p>
      </div>
      <div class="col-12">
        <a  href="https://docs.google.com/document/d/1Y54YMec-Jw_kEM0jfOv4dBI7vSOf5hpw_muShCWnzx8/edit?usp=sharing" target="_blank" >
          <h1 class=" text-center">Resume <i title="See my Resume!" class="mdi mdi-folder"></i></h1>
        </a>
      </div>
      <div class="col-12 d-flex justify-content-center text-center" >
        <section class="slide-divide1" >
          <div class="dot1"></div>
        </section>
      </div>
      <div class="col-md-6 col-12 d-flex justify-content-end">
        <section class="row justify-content-center">
          <div class="col-10"><h2 class="text-white">Education</h2></div>
          <div class="col-md-10 col-12">
            <section class="card bg-grey">
              <div class="bold fs-4 px-3">Full-Stack Immersive Course</div>
              <div class="italic bold px-3">CodeWorks 2023</div>
              <div class="p-3 px-3">Over 500 hours developing and testing fullstack applications while implementing scrum and agile practices in a team enviroment. Learned different back end languages including node and express, C# and Dotnet. While using a JavaScript front end with Vue.js framework.</div>
            </section>
          </div>
          <div class="col-md-10 col-12">
            <section class="card bg-grey my-2">
              <div class="bold fs-4 px-3">Computer Science </div>
              <div class="italic bold px-3">College of Western Idaho 2018-2020</div>
              <div class="p-3"> </div>
            </section>
          </div>
          <!-- <div class="col-10">
            <section class="card bg-grey" style="height: 20vh;">
              <div class="">Full-Stack</div>
              <div class="">CodeWorks 2023</div>
              <div class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio, repellendus!</div>
            </section>
          </div> -->
        </section>
      </div>
      <div class="col-md-6 col-12 d-flex justify-content-end">
        <section class="row justify-content-center">
          <div class="col-md-10 col-12"><h2 class="text-white">Applications</h2></div>
          <div class="col-md-10 col-12">
            <section class="card bg-grey" >
              <div class="bold fs-4 px-3">CodeFitness</div>
              <div class="italic bold px-3">CodeWorks 2023</div>
              <div class="p-3">Application to create routines and search a exercise API for different exercises. Able to save exercises to routines as well as many other features. Node + Express BackEnd, Vue.js FrontEnd, mongoDB DataBase.</div>
            </section>
          </div>
          <div class="col-md-10 col-12">
            <section class="card bg-grey my-2" >
              <div class="bold fs-4 px-3">Keeper</div>
              <div class="italic bold px-3">CodeWorks 2023</div>
              <div class="p-3">Application where users are able to create albums and photos. Then users can save other users photos as well as their own to their albums. Private vaults supported only viewable by creator. C# + DotNet BackEnd, Vue.js FrontEnd with mySQL DataBase.</div>
            </section>
          </div>
          <div class="col-md-10 col-12">
            <section class="card bg-grey" >
              <div class="bold fs-4 px-3">AllSpice</div>
              <div class="italic bold px-3">CodeWorks 2023</div>
              <div class="p-3">Application where users are able to create recipes and share with other users. Can favorite recipes to your account to easily access. C# + DotNet BackEnd, Vue.js FrontEnd with mySQL DataBase.</div>
            </section>
          </div>
        </section>
      </div>
      <div class="col-md-4 col-12 text-white">
        <div class="col-12 text-white text-center m-2"><h3>Languages</h3></div>
        <div class="col-12">
          <p>Dotnet | C# | MySQL | SQL DataBases | Dapper | JavaScript | Vue.js | React | HTML | CSS | Node.Js | Express | MongoDB | Mongoose</p>
        </div>
      </div>
      <div class="col-md-4 col-12 text-white">
        <div class="col-12 text-white text-center m-2"><h3>Technical Skills</h3></div>
        <div>
          <div class="col-12">
          <p>UI/UX | Solution Design | Fraud Prevention | Technical Experience | Computer Literacy | Command Line | MVC | OOP | Git | Git Action | Docker / Containers | Data Streaming | AWS </p>
        </div>

        </div>
      </div>
      <div class="col-md-4 col-12 text-white">
        <div class="col-12 text-white text-center m-2"><h3>Skills</h3></div>
        <div class="col-12">
          <p>Hard Working | Problem Solver | Life Long Learner | Determined | Confident | Friendly | Great at Multitasking | Positive | Communication Skills | Flexible | Committed | Enthusiasm | Innovation | Great working in a team</p>
        </div>
      </div>
    </section>

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
      <h2 class="text-white text-center"> <a title="Takes a while to load (due to OnRender Site hosted on)" href="https://tower-cqxd.onrender.com/#/" target="_blank"> Tower</a> <a href="https://github.com/Jasperdelight/towerCheckpoint" target="_blank"> <i title="GitHub Repo" class="mdi mdi-github"></i></a></h2>
      <div class="col-4">
        <a href="https://i.imgur.com/pw1WXl2.png" target="_blank" alt="tower1"><img src="https://i.imgur.com/pw1WXl2.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/iK3A0oZ.png" target="_blank" alt="tower2"><img src="https://i.imgur.com/iK3A0oZ.png" class="img-fluid" alt=""></a>
      </div>
      <div class="col-4">
        <a href="https://i.imgur.com/Um3N7cp.png" target="_blank" alt="tower3"><img src="https://i.imgur.com/Um3N7cp.png" class="img-fluid" alt=""></a>
      </div>
      <h2 class="text-white text-center">AllSpice <a href="https://github.com/Jasperdelight/allSpice" target="_blank"> <i title="GitHub Page" class="mdi mdi-github"></i> </a></h2>
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
