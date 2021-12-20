<template>
  <q-card class="project" flat bordered>
    <slot/>
    <q-separator/>
    <q-card-section>
      <div class="text-h4">{{ title }}</div>
      <div class="text-subtitle1">{{ description }}</div>
      <div class="text-subtitle1"><a :href="github" class="text-primary">GitHub</a></div>
    </q-card-section>
  </q-card>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  props: ['title', 'description', 'github'],
})
</script>

<style lang="scss" scoped>
.project {
  margin: 80px 0;
}
</style>
