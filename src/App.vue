<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style lang="scss">
@use "./assets/scss/variables.scss";
@use "./assets/scss/breakpoints.scss";
@use "./assets/scss/global.scss";
</style>
