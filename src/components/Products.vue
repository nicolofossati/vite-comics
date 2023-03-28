<script>
export default {
    data() {
        return {
            products: [
                {
                    "img": "buy-comics-digital-comics.png",
                    "title": "DIGITAL COMICS"
                },
                {
                    "img": "buy-comics-merchandise.png",
                    "title": "DC MERCHANDISE"
                },
                {
                    "img": "buy-comics-subscriptions.png",
                    "title": "SUBSCRIPTION"
                },
                {
                    "img": "buy-comics-shop-locator.png",
                    "title": "COMIC SHOP LOCATOR"
                },
                {
                    "img": "buy-dc-power-visa.svg",
                    "title": "CD POWER VISA"
                }
            ]
        }
    },
    methods: {
        getImageUrl(name) {
            return new URL(`../img/${name}`, import.meta.url).href;
        }
    }
}
</script>

<template>
    <div class="products-container debug">
        <div class="products-content">
            <div class="product" v-for="(product, index) in products" :key="`img-${index}`">
                <img :src="getImageUrl(product.img)">
                <div class="product-name"><span>{{ product.title }}</span></div>
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