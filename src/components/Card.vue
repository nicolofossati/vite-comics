<script>
export default {
    props: {
        thumb: String,
        series: String
    }
}

</script>

<template>
    <div class="card">
        <img :src="thumb" alt="">
        <span>{{ series }}</span>
    </div>
</template>

<style scoped lang="scss">
.card {
    display: flex;
    flex-direction: column;
    width: calc(100%/6 - 20px);
    padding: 10px;
    margin: 10px;

    img {
        width: 100%;
        aspect-ratio: 1/1;
    }

    span {
        text-align: center;
        font-weight: 500;
        color: white;
    }

}
</style>
