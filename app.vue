<script setup lang="ts">
onMounted(() => {
  setTimeout(() => {
    useTrackEvent('hello');
  }, 1000);
});
</script>

<template>
  <div>
    <NuxtRouteAnnouncer/>
    <NuxtWelcome/>
  </div>
</template>
