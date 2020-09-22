<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Hello Vue 3.0 + Vite" /> -->
  <div></div>
  <router-link to="/">hello</router-link>&nbsp;
  <router-link to="/todoList">todoList</router-link>
  <router-view></router-view>

</template>

<script lang="ts">
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
  },
}
</script>
