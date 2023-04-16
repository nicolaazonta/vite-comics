
<script>
    export default {
        name: 'comic',
        props: {
            img: String,
            text: String
        }
}
</script>

<template>
    <div class="col-2 d-flex flex-column">
        <img class="img-fluid"  :src="img" alt="">
        <p class="text-uppercase">{{ text }}</p>

    </div>
</template>

<style lang="scss" scoped>

</style>