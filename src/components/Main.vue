<!-- eslint-disable vue/multi-word-component-names -->
<script setup>
import MainSearch from "./MainSearch.vue";
import MainCards from "./MainCards.vue";
</script>

<template>
  <div class="wrapper">
    <MainSearch />
    <MainCards />
    <h1>Hello There</h1>
  </div>
</template>

<style scoped lang="postcss">
.wrapper {
  @apply container mx-auto flex flex-col gap-4 py-4;
}
</style>
