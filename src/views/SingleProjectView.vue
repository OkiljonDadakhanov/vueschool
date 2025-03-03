<script lang="ts" setup>
import { useRoute } from 'vue-router'

const route = useRoute()
const projectId = route.params?.id
</script>

<template>
  <div>
    <h1>Project Name</h1>
    <p>Project ID: {{ projectId }}</p>
  </div>
</template>
