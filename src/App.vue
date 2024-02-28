

<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
 
  <router-view/>
</template>
<script>

export default {
  components: {
    
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
#app {
  font-family: "Press Start 2P", system-ui;
  
  text-align: center;
  
}
::-webkit-scrollbar {
  display: none;
}
nav {
  padding: 30px;
  background-color: transparent !important;
}

nav a {
  font-weight: bold;
  color: white;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>
