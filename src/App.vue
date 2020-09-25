<template>
  <div id="app">
    <img alt="Vue logo" src="https://tr.rbxcdn.com/38e2b8adf7d7f18731c5aa4efc442f4a/420/420/Decal/Png">
    <anime/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import anime from '@/components/anime.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    anime
  }
}
</script>

<style>

#app {
  background-image: url(https://i.pinimg.com/originals/6b/04/16/6b04166d73e5af48ffecc373135bab7c.jpg);
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
