<template>
    <h1>Olá Mundo!</h1>
    <h2>Primeiro projeto em VUE 3</h2>
    <p>Este é apenas um teste</p>

</template>

<script lang="ts">

import { defineComponent } from 'vue'

export default defineComponent({
    name: 'OlaMundo'
})
</script>

<style scope>
body {
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
}

h1 {
    color: violet;
}

h2 {
    color: turquoise;
}
</style>