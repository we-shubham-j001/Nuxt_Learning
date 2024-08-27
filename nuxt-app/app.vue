<template>
  <a href ="#"@click="view('Home')">Home</a>
  <br>
  <a href ="#"@click="view('counter')">Counter</a>
    
  <NuxtPage/>

  <Home-welcome v-if="page === 'Home'" />
  <counter v-if="page === 'counter'" />
</template>

<script setup>
const page = ref("home");
function view(name) {
  page.value = name;
}
</script>
