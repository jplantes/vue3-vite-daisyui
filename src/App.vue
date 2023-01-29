<script setup>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavVar.vue'
</script>

<template>
  <NavBar />

  <div class="flex justify-center">
    <div class="flex justify-around w-96">
      <a href="https://vuejs.org/" target="_blank">
        <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
      </a>
      <a href="https://daisyui.com/" target="_blank">
        <img src="./assets/daisyui.svg" class="logo vue" alt="DaisyUI logo" />
      </a>
      <a href="https://vitejs.dev" target="_blank">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
      </a>
    </div>
  </div>
  <HelloWorld />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
