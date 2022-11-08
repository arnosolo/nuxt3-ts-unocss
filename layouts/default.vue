<script setup lang="ts">
import PageFooter from './PageFooter.vue'
import PageHeader from './PageHeader.vue'
</script>

<template>
  <div>
    <PageHeader />
    <slot />
    <PageFooter />
  </div>
</template>
