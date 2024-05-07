<script lang="ts">
export default {
  name: 'ExperiencePart',
}
</script>
<template>
  <div class="main">
    <div class="nameAndRole">
      <h6 class="name">Tair Sairanbekov</h6>
      <h3 class="role">Software Engineer</h3>
    </div>
    <div class="experience">
      <p class="info bigger">Constant improvement.</p>
      <p class="info smaller">
        In my free time, I am exploring other spheres of software engineering,
        such as Back-end. Specifically, I've started a journey to master Go
        language for the Back-end and do pet projects using this language.
        <br /> <br />
        I believe that one of the main skills for a software engineer is the
        ability to find solutions to a given problem, so I also improve this
        important skill by solving algorithmic problems, since this, in my
        opinion, is the type of problem that is difficult to simply memorize.
      </p>
      <div class="numbers">
        <div class="projectsNumber">
          <span class="gradientTitle">Projects Done</span>
          <span class="resultNumber">3+</span>
        </div>
        <div class="experienceNumber">
          <span class="gradientTitle">Experience</span>
          <span class="resultNumber">2+ Years</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import './ExperiencePart.css';
</style>
