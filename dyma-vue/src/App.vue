<template>
  <h1 :class="classtitle" :[idtitle]="classtitle">Bonjour monde</h1>
</template>

<script setup lang="ts">
  const classtitle = 'title'
  const idtitle = 'id'
</script>

<style scoped>

</style>
