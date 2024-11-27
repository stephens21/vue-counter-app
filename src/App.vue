<script setup>
import { ref } from 'vue';
   const count = ref(0);
</script>

<template>
  <main>
    <div>
    <h1>The current count is ...</h1>
    <h1>{{ count }}</h1>
    <button @click="count--">-</button>
    <button @click="count++">+</button>
  </div>
  </main>
  
</template>
<style scoped>
main{
  width: 100vw;
    height: 100vh;
    background-color: aliceblue;
    display: flex;
    align-items: center;
    justify-content: center;
}
div{
  text-align: center;
}
</style>