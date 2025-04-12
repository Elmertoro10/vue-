<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
    <div class="logos">
      <a href="https://vite.dev" target="_blank">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
      </a>
      <a href="https://vuejs.org/" target="_blank">
        <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
      </a>
    </div>

    <!-- Tu mensaje personalizado -->
    <h1 class="mt-4">¡Hola Mundo desde Vue! 🟢</h1>
    <p>Proyecto creado con Vite + Vue 3</p>

    <!-- Componente por defecto -->
    <HelloWorld msg="Vite + Vue" />
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 3rem;
  font-family: Arial, sans-serif;
}

.logos {
  display: flex;
  justify-content: center;
  gap: 3rem;
  margin-bottom: 2rem;
}

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
