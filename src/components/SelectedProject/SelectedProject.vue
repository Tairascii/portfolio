<script lang="ts">
export default {
  name: 'SelectedProject',
}
</script>
<template>
  <section id="selectedProjects" class="main">
    <h2 class="title">Selected Projects</h2>
    <p class="subtitle">
      I do love trying my skills on different types of project.<br />
      Here is my favorite ones
    </p>
    <div class="humanType">
      <span class="projectName"> MonkeyType</span>
      <div class="buttons">
        <button class="github">View on GitHub</button>
        <button class="link">Link</button>
      </div>
    </div>
    <div class="spotify">
      <span class="projectName"> Spotify </span>
      <div class="buttons">
        <button class="github">View on GitHub</button>
        <button class="link">Link</button>
      </div>
    </div>
  </section>
</template>
<style scoped>
@import './SelectedProject.css';
</style>
