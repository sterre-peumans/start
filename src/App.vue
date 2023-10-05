<script setup>
import { RouterLink, RouterView } from 'vue-router'


</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <li>
          <ul><h1 class="text-xl font-extrabold">TITLE OF YOU WEBSITE</h1></ul>
          <ul><h4>SECOND COURSE TAILWIND</h4></ul>
          <ul><RouterLink to="/">Home</RouterLink></ul>
          <ul><RouterLink to="/about">About</RouterLink></ul>
          <ul><RouterLink to="/works">Works</RouterLink></ul>
        </li>  
      </nav>
    </div>
  </header>
  <RouterView />
</template>

<style scoped>
</style>
