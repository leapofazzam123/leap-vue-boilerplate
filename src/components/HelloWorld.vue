<script setup lang="ts">
import { ref } from "vue"

defineProps<{ msg: string }>()
</script>

<template>
  <h1>{{ msg }}</h1>
  <p>
    This is my website boilerplate using Vue 3, TypeScript, Vite and Tailwind
    CSS. You can use this boilerplate for your project.
  </p>
  <p>
    You can try to edit <code>src/components/HelloWorld.vue</code> and see your
    changes without refreshing your browser.
  </p>
</template>
