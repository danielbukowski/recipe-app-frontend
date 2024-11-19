<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header class="flex flex-col items-center">
    <img alt="Vue logo" class="logo mt-2" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper ">
      <HelloWorld msg="You did it!" />

      <nav class="justify-self-center">
        <RouterLink to="/">Home</RouterLink>
      </nav>
    </div>
  </header>

  <div>
    <RouterView />
  </div>
</template>