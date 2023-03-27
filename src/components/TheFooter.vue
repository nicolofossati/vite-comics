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

.debug .footer-down-container {
    background-color: #303030;
}



/* FINE DEBUG */

.footer-top-container {
    background-image: url(../img/footer-bg.jpg);
}

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
    padding: 0 10px;
}

.links-container .links ul li {
    list-style-type: none;
    color: rgba(167, 167, 167, 0.595);
}

.links-container .links h3 {
    color: white;
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