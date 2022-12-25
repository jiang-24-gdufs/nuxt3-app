<script setup lang="ts">
const props = defineProps<{
  title?: string,
}>()

</script>

<template>
  <header border>{{ title ?? 'Default Title' }}</header>
  <div>
    <slot/>
  </div>
</template>
