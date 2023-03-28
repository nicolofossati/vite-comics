<script>
import Card from './Card.vue';

export default {
    components: {
        Card
    },
    props: {
        titles: Array
    }
}
</script>

<template>
    <div class="main-container">
        <div class="main-content">
            <span class="current-series-tag">CURRENT SERIES</span>
            <div class="current-series-container">
                <div v-for="title in titles" class="card-wrapper">
                    <Card :thumb="title.thumb" :series="title.series" />
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
//@use "./partials/colorsVar as *";

.main-container {
    background-color: #1c1c1c;
}

.main-content {
    position: relative;
    max-width: 80%;
    margin: auto;
    padding: 20px 0;
}


.current-series-tag {
    color: white;
    position: absolute;
    z-index: 2;
    padding: 10px;
    background-color: #0282f9;
    height: 40px;
    top: -20px;
    left: 0px;
    box-shadow: #1c1c1c;
}

.current-series-container {
    display: flex;
    flex-wrap: wrap;
}

.card-wrapper {
    display: contents;
}
</style>