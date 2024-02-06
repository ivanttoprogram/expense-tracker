<template>
    <h4>Your Balance</h4>
    <h1 id="balance"> {{ total }}</h1>
</template>

<script setup>
 
import { DefineProps } from 'vue';

const props = defineProps({
    total: {
        type: Number, 
        require: true,
    }
})

</script>