<script setup>
import Head from "./components/Head.vue"

import { RouterView } from "vue-router";


</script>

<template>
  <div class="app"> 
      <Head/>

      <RouterView/>

  </div>

</template>

<style scoped>
.app{                           
  width: 100%;
  min-height: 100vh;
  background: #2323b3;
}
</style>

