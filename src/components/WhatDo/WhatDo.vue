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
    <span class="title">What I work with</span>
    <div class="logos">
      <div class="imageWrapper">
        <img src="/src/assets/images/go.png" alt="golang" class="logo" />
        <span class="logoName">GoLang</span>
      </div>
      <div class="imageWrapper">
        <img src="/src/assets/images/ts.svg" alt="ts" class="logo" />
        <span class="logoName">TypeScript</span>
      </div>
      <div class="imageWrapper">
        <img src="/src/assets/images/react.svg" alt="react" class="logo" />
        <span class="logoName">ReactJS</span>
      </div>
      <div class="imageWrapper">
        <img src="/src/assets/images/kafka.png" alt="kafka" class="logo" />
        <span class="logoName">Apache Kafka</span>
      </div>
      <div class="imageWrapper">
        <img src="/src/assets/images/pos.svg" alt="postgreSQL" class="logo" />
        <span class="logoName">PostgreSQL</span>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import './WhatDo.css';
</style>
