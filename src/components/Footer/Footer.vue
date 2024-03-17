<script lang="ts">
import { links } from './links'

export default {
  name: 'FooterComponent',
  setup() {
    return {
      links,
    }
  },
}
</script>
<template>
  <footer class="footer">
    <span class="title"> PORTFOLIO</span>
    <div class="links">
      <a href="https://github.com/Tairascii" class="link">
        <img src="/src/assets/images/github.svg" alt="github" class="logo" />
      </a>
      <a href="https://www.linkedin.com/in/tair-sairanbekov/" class="link">
        <img
          src="/src/assets/images/linkedin.svg"
          alt="linkedin"
          class="logo"
        />
      </a>
      <a href="https://leetcode.com/tair_sairanbekov/" class="link">
        <img
          src="/src/assets/images/leetcode.svg"
          alt="leetcode"
          class="logo"
        />
      </a>
    </div>
  </footer>
</template>

<style scoped>
@import './Footer.css';
</style>
