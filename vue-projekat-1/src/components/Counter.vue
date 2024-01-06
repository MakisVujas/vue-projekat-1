<script setup>
import { ref } from 'vue'

let counter = ref(0)

</script>



<template>
    <div>
        <button>{{ counter }}</button>
    </div>
</template>

<style>

div {
    background-color: yellow;
    display: flex;
    justify-content: center;
    
    }
div button {
    font-size: 41px;
}
 

</style>