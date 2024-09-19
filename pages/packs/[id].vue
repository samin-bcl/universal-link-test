<template>
  <div>
    {{ id }}
    <br>
    <a :href="`get-pack/${id}`">Install Pack</a>
  </div>
</template>

<script lang="ts" setup>
const { id } = useRoute().params;
</script>

<style>

</style>