<template>
  <h2>DefaultPageLayout</h2>
  <SidebarPanel />
  <div class="container">
    <RouterView />
  </div>
</template>

<script setup lang="ts">
import SidebarPanel from '@renderer/components/panels/SidebarPanel.vue'
</script>

<style lang="scss"></style>
