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
      <span v-for="link in links" :key="link.url">
        <a :href="link.url" class="link">
          <img :src="link.image" :alt="link.alt" class="logo" />
        </a>
      </span>
    </div>
  </footer>
</template>

<style scoped>
@import './Footer.css';
</style>
