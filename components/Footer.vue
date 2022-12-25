<script setup lang="ts">
const props = defineProps<{
  link?: string,
}>()

</script>

<template>
  <footer>{{ link ?? 'Default Footer' }}</footer>
  <div>
    <slot/>
  </div>
</template>
