<script setup lang="ts">
import { ref } from 'vue';
import ListItem from './ListItem.vue';
const count = ref(0)
</script>

<template>
    <v-btn @click="count++" variant="elevated" color="#84a2d4">{{ count }}</v-btn>
    <ListItem />
</template>

<style scoped></style>
