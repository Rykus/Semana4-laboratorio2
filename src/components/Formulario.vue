<template>
    <div>
        <input type="text" v-model="inputValue">
        <div>
            {{inputValue}}
        </div>
    </div>
</template>

<script setup>

import {ref} from 'vue';
//al hacer ref con el imput del valor se guarda y luego lo imprimimos debajo.
const inputValue = ref('valor por defecto');

</script>

<style scoped>

</style>
