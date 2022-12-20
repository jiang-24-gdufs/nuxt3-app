<template>
    <div>
        <h1>Hello World</h1>
        <p>Current time: {{ time }}</p>
        <slot></slot>
    </div>
</template>
  
<script setup lang="ts">
const time = useTime() // Same as useState('color')
</script>