<script setup>
import HelloWorld from './components/HelloWorld.vue'
import profile from './assets/profile.png'
</script>

<template>
  <img :src="profile" alt="Pessoa com camiseta da Azion em um escritório" class="profile" />
  <HelloWorld />
</template>

<style scoped>
.profile {
  display: block;
  max-width: 100%;
  height: auto;
  margin: 0 auto;
}
</style>
