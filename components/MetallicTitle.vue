<template>
  <h1 class="metallic uppercase">
    <slot>
      {{ title }}
    </slot>
  </h1>
</template>

<script setup lang="ts">
defineProps<{
  title: string
}>()
</script>


<style scoped>
.metallic {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.25em;
  font-weight: bold;
  background: linear-gradient(#262626,#eaeaea,#262626);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent !important;
}
</style>