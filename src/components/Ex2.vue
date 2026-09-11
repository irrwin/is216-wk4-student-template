<script setup>
    import { ref } from 'vue'

    // Add code here
    const image = ref('/public/assets/me.png')
    const width = ref(300)
    const height = ref(300)
</script>

<template>

    <!-- Add code here -->
   <img v-bind:src="image" :width="width" :height="height">
</template>
