<script setup>
const name = 'Guntur Lailam Yuro'

const showName = () =>console.log(name)
</script>

<template>
    <h1>{{ name }}</h1>
    <button @click="showName">Show name</button>
</template>