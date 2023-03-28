<script></script>

<template>
    <div class="products-container debug">
        <div class="products-content">
            <div class="product">
                <img src="../img/buy-comics-digital-comics.png">
                <div class="product-name"><span>DIGITAL COMICS</span></div>
            </div>
            <div class="product">
                <img src="../img/buy-comics-merchandise.png">
                <div class="product-name"><span>DC MERCHANDISE</span></div>
            </div>
            <div class="product">
                <img src="../img/buy-comics-subscriptions.png">
                <div class="product-name"><span>SUBSCRIPTION</span></div>
            </div>
            <div class="product">
                <img src="../img/buy-comics-shop-locator.png">
                <div class="product-name"><span>COMIC SHOP LOCATOR</span></div>
            </div>
            <div class="product">
                <img src="../img/buy-dc-power-visa.svg">
                <div class="product-name"><span>CD POWER VISA</span></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.products-container {
    background-color: #0282f9;
    height: 100px;
    padding: 25px;
}

.products-content {
    max-width: 80%;
    height: 100%;
    margin: auto;
    padding: 5px 20px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}


.product {
    width: calc(100%/5 - 10px);
    display: flex;
}

.product-name {
    display: flex;
    align-items: center;
    padding: 0 10px;
    color: white;
}
</style>