<template>
 
  <div class="home" :style="image">
    <NavBarComp/>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <FooterComp/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import NavBarComp from '@/components/NavBarComp.vue'
import FooterComp from '@/components/FooterComp.vue'
export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    NavBarComp,
    FooterComp
  },
  data() {
    return {
      image: {backgroundImage: "url(https://i.postimg.cc/5t2hKnZX/wp12749811.jpg)"}
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
</style>