<script setup>
import { ref } from 'vue'

let counter = ref(0)



</script>



<template>
    
    <div>
        <h1>{{ counter }}</h1>
    </div>
    <div class="container">
        <button>+</button>
        <button>-</button>
    </div>
    
</template>

<style>
    
h1 {
    font-size: 41px;
    text-align: center;
}
.container {
    text-align: center;
    height: 40px;
    
}

button {
    padding: 15px 15px;
    font-size: 22px;
}
 

</style>