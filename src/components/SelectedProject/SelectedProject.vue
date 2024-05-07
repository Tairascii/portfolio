<script lang="ts">
export default {
  name: 'SelectedProject',
}
</script>
<template>
  <section id="selectedProjects" class="main">
    <h2 class="title">Selected Projects</h2>
    <p class="subtitle">
      I do love trying my skills on different types of projects.<br />
      Here are my favorite ones
    </p>
    <div class="humanType">
      <span class="projectName">Typo</span>
      <div class="buttons">
        <a
          class="github"
          href="https://github.com/Tairascii/typo"
          target="_blank"
          >View on GitHub</a
        >
        <a
          class="link"
          href="https://typo-tairasciis-projects.vercel.app/"
          target="_blank"
          >Link</a
        >
      </div>
    </div>
    <div class="spotify">
      <span class="projectName"> Spotify </span>
      <div class="buttons">
        <a
          class="github"
          href="https://github.com/Tairascii/spotify"
          target="_blank"
          >View on GitHub</a
        >
      </div>
    </div>
  </section>
</template>
<style scoped>
@import './SelectedProject.css';
</style>
