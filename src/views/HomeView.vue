<template>
  <div class="home" :style="image">
    <NavBarComp />
    <div class="landing">
      <div class="name">
        <h1>
          Cheslyn Herman Portfolio
        </h1>
      </div>
      <div class="insert">
        <h2>Insert Coin</h2>
      </div>
      <div class="startbtn">
        <router-link to="/about">

          <button class="start">
            Player 1 Start
          </button>
        </router-link>
      </div>
    </div>
    <FooterComp />
  </div>
</template>

<script>
// @ is an alias to /src

import NavBarComp from '@/components/NavBarComp.vue'
import FooterComp from '@/components/FooterComp.vue'
export default {
  name: 'HomeView',
  components: {
    NavBarComp,
    FooterComp
  },
  data() {
    return {
      image: { backgroundImage: "url(https://i.postimg.cc/5t2hKnZX/wp12749811.jpg)" }
    }
  }

}
</script>

<style scoped>
.home {

  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  object-fit: cover;
}

.landing {
  /* border: 1px solid white; */
  height: 70vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
}

.name,
.insert {
  margin-bottom: 40px;
}

.insert {
  -webkit-animation: fade-in 1s ease-in infinite;
  animation: fade-in 1s ease-in infinite;
}

@-webkit-keyframes fade-in {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

.start {
  padding: 15px;
  width: 450px;
  color: white;
  background: transparent;
  border: 1px solid white;
  box-shadow: 0 0 0 0 transparent;
    -webkit-transition: all 0.2s ease-in;
    -moz-transition: all 0.2s ease-in;
    transition: all 0.2s ease-in;
}



.start:hover {
  
     
    box-shadow: 0 0 30px 5px white;
    -webkit-transition: all 0.2s ease-out;
    -moz-transition: all 0.2s ease-out;
    transition: all 0.2s ease-out;
}
h2 {
  font-size: 26px;
}


@media only screen and (max-width: 480px) {
  .start {
    width: 90%;
  }
}
</style>