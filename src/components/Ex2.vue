<script setup>
    import { ref } from 'vue'

    // Add code here
    const image = ref('/assets/me.png')
    const width = ref(200)
    const height = ref(200)

    const myObj = ref({
        width: 200,
        height: 200,
        src: 'assets/me.png'
    })
</script>

<template>

    <!-- Add code here -->
   <img v-bind:src="image" :width="width" :height="height"/>

   <img v-bind="myObj"/>
</template>
