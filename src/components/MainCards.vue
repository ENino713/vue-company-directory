<script setup>
import MainCardsSingle from "./MainCardsSingle.vue";
</script>

<template>
    <div class="sub-wrapper">
        <MainCardsSingle v-for="n in 20" />
    </div>
</template>

<style scoped lang="postcss">
.sub-wrapper {
    @apply grid gap-4 grid-cols-2;
}
</style>
