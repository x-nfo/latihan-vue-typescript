<script setup lang="ts">
import { ref, reactive } from 'vue';

const user = ref<String | Number>();

user.value = 12345;

type Color = 'green' | 'pink' | 'orange';

const colors = ref<Color>('pink');
</script>

<template>
    {{ user }}
    {{ colors }}
</template>
