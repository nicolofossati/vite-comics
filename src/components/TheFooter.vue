<script>
export default {
    data() {
        return {
            footerLinks: [
                {
                    title: "DC COMICS",
                    links: ['Characters', 'Comics', 'Movies', 'TV', 'Games', 'Videos', 'News']
                },
                {
                    title: "SHOP",
                    links: ['Shop DC', 'Shop DC Collectibles']
                },
                {
                    title: "DC",
                    links: ['Terms Of USe', 'Privacy Policy (New)', 'Ad Choices', 'Advertising', 'Jobs', 'Subscriptions', 'Talent Workshops', 'CPSC Certificates', 'Ratings', 'Shop Help', 'Contact Us']
                },
                {
                    title: "SITES",
                    links: ['DC', 'MAD Magazine', 'DC Kids', 'DC Universe', 'DC Power Visa']
                }
            ]
        }
    }
}
</script>

<template>
    <div class="footer-container debug">
        <div class="footer-top-container">
            <div class="footer-top">
                <div class="links-container">
                    <div class="links" v-for="obj in footerLinks">
                        <h3>{{ obj.title }}</h3>
                        <ul>
                            <li v-for="(link, index) in obj.links">{{ link }}</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <div class="footer-down-container">
            <div class="footer-down">
                <div class="bttn">BUTTON</div>
                <div class="social">
                    <span>FOLLOW US</span>
                    <div></div>
                    <div></div>
                    <div></div>
                    <div></div>
                    <div></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* DEBUG */
.debug .footer-top-container {
    background-color: black;
}

.debug .footer-down-container {
    background-color: #303030;
}

.debug .footer-top .links-container {
    height: 200px;
    background-color: aqua;
}

.debug .links-container>div {
    width: calc(100%/3);
    background-color: blue;
    border: 2px solid white;
}

/* FINE DEBUG */



.footer-top {
    max-width: 80%;
    margin: auto;
    padding: 30px 0;
}

.footer-top .links-container {
    width: calc(100%/3);
    display: flex;
}

.links-container>div {
    width: calc(100%/3);
}


.footer-down {
    max-width: 60%;
    margin: auto;
    padding: 15px 0;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
</style>