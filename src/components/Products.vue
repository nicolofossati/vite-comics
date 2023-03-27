<script></script>

<template>
    <div class="products-container debug">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
</template>

<style scoped>
/*DEBUG */
.debug {
    height: 100px;
}

.debug div {
    background-color: white;
    width: calc(100%/5 - 10px);
}

/* FINE DEBUG */
.products-container {
    padding: 5px 20px;
    background-color: #0282f9;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
</style>