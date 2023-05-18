<script>
export default {
    name: "AppTitle",
}
</script>

<template>
    <h1 class="green">La mia prima app con <span class="viteText">Vite!</span></h1>
</template>

<style scoped>
h1 > span.viteText {
    color: aqua;
    text-decoration: underline;
}
</style>