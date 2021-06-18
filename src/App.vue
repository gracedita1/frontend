<template>
  <router-link to = "/"> Halaman Auth</router-link> &nbsp;
  <router-link to = "/todo"> Halaman Todo</router-link> &nbsp;
  <router-link to = "/user"> Halaman User</router-link>
  <router-view></router-view>
</template>

<script setup>
import Todo from './components/Todo.vue'
import User from './components/User.vue'
</script>


<style>
#app {

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}
</style>
