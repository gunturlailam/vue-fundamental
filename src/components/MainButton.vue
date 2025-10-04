<script setup>
const isLoading = false
const  buttonAttr = {
    disable:isLoading,
    class:'text-3xl bg-black text-white'
}
const renderIsLoading = () => {
    if (isLoading){ 
        return "Loading"
    } else {
        return "Submit"
    }
}
</script>

<template>
    <button :disabled="buttonAttr" :id="`id-${buttonAttr.class}`">
        {{ renderIsLoading ()}}
    </button>
</template>

<script scoped></script>