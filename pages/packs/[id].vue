<template>
  <div>
    {{ id }}
    <br>
    <a :href="`combraincraftstickemaker://${id}`">Install Pack</a>
  </div>
</template>

<script lang="ts" setup>
const { id } = useRoute().params;
</script>

<style>

</style>