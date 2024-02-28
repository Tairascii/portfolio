<script setup lang="ts">
import { UpperSection } from '../UpperSection'
import { Divider } from '../Divider'
import { SelectedProject } from '../SelectedProject'
</script>
<script lang="ts">
export default {
  name: 'MainPart',
}
</script>
<template>
  <UpperSection />
  <Divider />
  <SelectedProject />
</template>
