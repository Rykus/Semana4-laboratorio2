<template >
    <div v-if="isRender">Estoy o no?</div>
    <button @click="onClick">esto lo decide</button>
</template>

<script setup>
import { ref } from 'vue';
 
const isRender = ref(true);

const onClick = () =>{
    isRender.value = !isRender.value
};
</script>

<style scoped>

</style>