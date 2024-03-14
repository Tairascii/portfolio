<script lang="ts">
export default {
  name: 'UpperSection',
}
</script>
<template>
  <div class="main">
    <div class="text">
      <div class="mainText">
        <span class="name">Hi, I am Tair,</span><br />
        <span class="about">Software Engineer<br />from Almaty</span>
      </div>

      <div class="subtitle">
        A Software Engineer from Almaty. I specialize at Front-end <br />
        but also a Back-end enthusiast
      </div>
      <div class="buttons">
        <button class="buttonMain gradientButton">GET IN TOUCH</button>
        <button class="buttonMain">VIEW ALL WORKS</button>
      </div>
    </div>
    <div class="imageWraper">
      <img src="../../assets/images/me.jpg" class="image" />
    </div>
  </div>
</template>
<style scoped>
@import './UpperSection.css';
</style>
