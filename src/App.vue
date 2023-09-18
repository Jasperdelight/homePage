<template>
  <header class="d-flex justify-content-center bg-black sticky-top">
    <Navbar />
  </header>
  <main class="bg-black">
    <router-view />
  </main>
</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
import Navbar from './components/Navbar.vue'

export default {
  setup() {
    
    return {
      appState: computed(() => AppState)
    }
  },
  components: { Navbar }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";

:root{
  --main-height: calc(100vh - 32px - 64px);
}


footer {
  display: grid;
  place-content: center;
  height: 32px;
}
.slide-divide{
position: relative;
border-top: 5px solid rgb(255, 102, 0);
width: 10vh;
}
.dot {
            width: 15px;
            height: 15px;
            background-color: var(--bs-warning);
            border-radius: 50%;
            top: -10px;
            position: absolute;
            animation: moveDot 4s linear infinite;
        }

        @keyframes moveDot {
            0%, 100% {
                left: -10%;
            }
            50% {
                left: 90%;
            }
        }
        #overlay-effect {
    animation-duration: 3s;
    animation-fill-mode: both;
    animation-timing-function: ease-in-out;
    background-color: #181818;
    bottom: 0;
    display: block;
    position: fixed;
    top: 0;
    left: -50%;
    transform: translateY(100%);
    width: 150%;
    z-index: 99999;
}
#overlay-effect.animate-up {
    animation-name: overlayEffectUp;
}
#overlay-effect.animate-down {
    animation-name: overlayEffectDown;
}
@keyframes overlayEffectUp{
  0% {
    transform: translateY(0%);
}

  30% {
    transform: translateY(100%);
}

//   60% {
//     transform: translateY(100%);
// }
100% {
    transform: translateY(200%);
}
}

@keyframes overlayEffectDown{
  0%{
    transform: translateY(0%);
  }
 


30% {
    transform: translateY(-100%);
}

100% {
    transform: translateY(-200%);
}
}
</style>
