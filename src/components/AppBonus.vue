<script>
export default {
    name: "AppBonus",
    data() {
        return {
            img: "src/assets/img/jumbotron.webp"
        }
    }
}
</script>

<template>
    <div>
        <img :src="img" alt="">
    </div>
</template>

<style scoped>
img {
    max-width: 100%;
    width: 900px;
}
</style>