<script>
    // esporto ciò che voglio rendere disponibile
    export default {
        data() {
            return {
                message: 'La mia prima app con Vite!'
            }
        }
    }
</script>

<template>
  <h1>{{ message }}</h1>
</template>

<style scoped>
    h1 {
        color: rgb(0, 193, 200);
    }
</style>