<template>
  <h3 class="text-center">Big projects</h3>
  <Project
    title="thlink"
    description="Graph cloud/ note-taking app. Inspired by Luhmann's Zettelkasten and Notion."
    github="https://github.com/thlink-hq"
  >
    <q-img src="thlink.png" width="100%" height="auto"/>
  </Project>
  <Project
    title="The media and climate change"
    description="How much attention does climate change get in different countries? How do newspapers write about climate change, what could they do better?"
    github="https://github.com/juliuskrahn/media-analysis-climate-change"
  >
    <q-img src="climate-change.png" width="100%" height="auto"/>
  </Project>
  <Project
    title="Taskstack"
    description="A Kanban Project Management web-app with chat... (initially for homeschooling in corona times)."
    github="https://github.com/juliuskrahn/Taskstack"
  >
    <iframe width="100%" height="450px" src="https://www.youtube.com/embed/BcopSXRtPjQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </Project>
  <Project
    title="PixelPaint"
    description="A pixel level drawing program."
    github="https://github.com/juliuskrahn/PixelPaint"
  >
    <q-img src="pixelpaint.png" width="100%" height="auto"/>
  </Project>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Project from 'components/Project.vue';

export default defineComponent({
  components: { Project },
})
</script>
