<template >
    <div v-for="element in data" :key="element.title">
    {{element.title}}, {{element.description}}, {{element.content}}
    </div>
</template>

<script setup>
const data = [
    {
        title: 'Leo',
        description: 'valientes',
        content: 'julio-agosto'
    },
    {
        title: 'cancer',
        description: 'sensibles',
        content: 'junio-julio'
    },
    {
        title: 'geminis',
        description: 'Duales',
        content: 'mayo-junio'
    },
]
</script>

<style scoped>

</style>