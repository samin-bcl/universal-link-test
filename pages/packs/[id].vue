<template>
  <div>
    {{ id }}
    <br>
    <NuxtLink :to="`get-pack/${id}`">Install Pack</NuxtLink>
  </div>
</template>

<script lang="ts" setup>
const { id } = useRoute().params;
</script>

<style>

</style>