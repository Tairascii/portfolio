<script lang="ts">
import { logos } from './logos'
export default {
  name: 'WhatDo',
  setup() {
    return {
      logos,
    }
  },
}
</script>
<template>
  <div class="main">
    <span class="title">What I do</span>
    <div class="logos">
      <div v-for="logo in logos" class="imageWrapper">
        <img :key="logo.alt" :src="logo.src" :alt="logo.alt" class="logo" />
        <span class="logoName">{{ logo.name }}</span>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import './WhatDo.css';
</style>
