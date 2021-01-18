<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <br>
  <router-link to="/">Home</router-link> | 
  <router-link to="/about">About</router-link>
  <router-view></router-view>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
