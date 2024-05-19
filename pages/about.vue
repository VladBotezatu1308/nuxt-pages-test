<template>
  <div>
    <p>This is the about page</p>
    <p>{{ data }}</p>
  </div>
</template>

<script lang="ts" setup>
  const { data } = useFetch('/api/data')
</script>

<style>

</style>