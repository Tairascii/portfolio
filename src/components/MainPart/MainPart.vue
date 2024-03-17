<script setup lang="ts">
import { UpperSection } from '../UpperSection'
import { Divider } from '../Divider'
import { SelectedProject } from '../SelectedProject'
import { ExperiencePart } from '../ExperiencePart'
import { WhatDo } from '../WhatDo'
import { InspirationPart } from '../InspirationPart'
import { Footer } from '../Footer'
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
    <WhatDo />
    <InspirationPart />
    <Footer />
  </main>
</template>
