<script setup>
defineProps(["buttonText"])
</script>


<template>
   <button>{{ buttonText }}</button> 
</template>

<style scoped>
 button{
    background-color: white;
    padding: 12px 32px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    border-radius: 48px;
 }
</style>