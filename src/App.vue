<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
// import HelloWorld from './components/HelloWorld.vue'
// import AnyOtherUI from './components/AnyOtherUI.vue'
// import Vue from 'vue'
// import ElementUI from 'element-ui'
// import 'element-ui/lib/theme-chalk/index.css';
// Vue.use(ElementUI);
import { NDivider, NButton } from 'naive-ui'
</script>

<template>
  <!-- <AnyOtherUI /> -->
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Hello Vue 3 + TypeScript + Vite + Element-UI" /> -->
  <div id="nav">
    <router-link to="/">
      <n-button quaternary round type="primary">
        Home
      </n-button>
    </router-link>
    <!-- <n-divider vertical /> -->
    <router-link to="/About">
      <n-button quaternary round type="primary">
        About
      </n-button>
    </router-link>
    <!-- <n-divider /> -->
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}

a {
  text-decoration-line: none;
}
</style>
