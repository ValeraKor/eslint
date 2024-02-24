<script setup lang="ts">
  import HelloWorld from '@/components/HelloWorld.vue';
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style lang="scss">
  .logo {
    display: block;
    height: 6em;
    padding: 1.5em;
    background-color: #42b883aa;
    border: #42b883aa 1px solid;
    filter: drop-shadow(0 0 2em #646cffaa);
    transition: filter 300ms;
    will-change: filter;
  }
  .logo:hover {
    bottom: 0;
    text-emphasis: none;
  }
  .logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
  }
</style>
