<script setup lang="ts">
import { UpperSection } from '../UpperSection'
import { Divider } from '../Divider'
import { SelectedProject } from '../SelectedProject'
import { ExperiencePart } from '../ExperiencePart'
</script>
<script lang="ts">
export default {
  name: 'MainPart',
}
</script>
<template>
  <main>
    <UpperSection />
    <Divider />
    <SelectedProject />
    <ExperiencePart />
  </main>
</template>
