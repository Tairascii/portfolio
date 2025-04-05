<script lang="ts">
export default {
  name: 'UpperSection',
}
</script>
<template>
  <div class="main">
    <div class="text">
      <div class="mainText">
        <span class="name">Hi! Tair,</span><br />
        <span class="about">a Software Engineer<br />from Almaty</span>
      </div>

      <div class="subtitle">
        A Software Engineer from Almaty. I specialize at Back-end, <br />
        and I am a Front-end enthusiast
      </div>
      <div class="buttons">
        <a href="/files/Tair_Sairanbekov_Backend.pdf" download class="linkMain gradientLink">RESUME</a>
        <a href="#selectedProjects" class="linkMain">VIEW ALL WORKS</a>
      </div>
    </div>
    <div class="imageWraper">
      <img src="/src/assets/images/me.jpg" class="image" />
    </div>
  </div>
</template>
<style scoped>
@import './UpperSection.css';
</style>
