<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <h1 class="c" style="margin-bottom: 4.5rem; font-size: 3.1rem;">База знаний</h1>

  <ul class="menu">
    <li><RouterLink to="/scratch">Scratch</RouterLink></li>
    <li><RouterLink to="/construct-2">Construct 2</RouterLink></li>
  </ul>
</template>