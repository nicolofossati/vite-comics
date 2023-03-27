<script></script>

<template>
    <div class="products-container debug">
        <div class="products-content">
            <div></div>
            <div></div>
            <div></div>
            <div></div>
            <div></div>
        </div>
    </div>
</template>

<style scoped>
/*DEBUG */
.debug {
    height: 100px;
}

.debug .products-content>div {
    background-color: white;
    width: calc(100%/5 - 10px);
}

/* FINE DEBUG */
.products-container {
    background-color: #0282f9;
}

.products-content {
    max-width: 60%;
    height: 100%;
    margin: auto;
    padding: 5px 20px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
</style>