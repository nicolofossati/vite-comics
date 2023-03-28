<script>
</script>

<template>
    <div class="main-container">
        <div class="main-content">
            <span class="current-series-tag">CURRENT SERIES</span>
            <div class="current-series-container">
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
                </div>
                <div class="card">
                    <img src="https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640" alt="">
                    <span>ACTION COMICS</span>
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

//   CARD


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












////////////////////
</style>