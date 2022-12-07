<script>
export default {
    data() {
        return {
            count: 0,
            saluto: "La mia prima app con Vite!"
        }

    }
}
</script>

<template>
    <h1 id="Title">{{ saluto }}</h1>
</template>

<style scoped>
#title {
    color: red;
}
</style>
