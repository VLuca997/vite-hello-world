<script >
import AppTitle from './components/AppTitle.vue'   //importato
import AppHero from './components/AppHero.vue'   //importato
export default {
  data() {
    return { count: 0 }
  },
  // dichiarazione
  components: {
    AppTitle, AppHero
  }
}
</script>

<template>
    <AppTitle /> <!-- MIO COMPONENTE -->
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  
  <h1>{{ msg }}</h1>

<div class="card">
  <button type="button" @click="count++">count is {{ count }}</button>
</div>
<AppHero />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
