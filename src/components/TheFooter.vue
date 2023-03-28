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
                <div class="bttn">SING-UP NOW!</div>
                <div class="social">
                    <span>FOLLOW US</span>
                    <img src="../img/footer-facebook.png" alt="fb logo">
                    <img src="../img/footer-twitter.png" alt="twitter logo">
                    <img src="../img/footer-youtube.png" alt="yt logo">
                    <img src="../img/footer-pinterest.png" alt="pinterest logo">
                    <img src="../img/footer-periscope.png" alt="perscope logo">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.footer-top-container {
    background-image: url(../img/footer-bg.jpg);
}

.footer-top {
    max-width: 80%;
    margin: auto;
    padding: 30px 0;

    .links-container {
        display: flex;
        flex-wrap: wrap;

        &>div {
            width: calc(100%/8);
            padding: 0 10px;
        }

        .links ul li {
            list-style-type: none;
            color: rgba(167, 167, 167, 0.595);
        }

        .links h3 {
            color: white;
        }
    }
}

.footer-down-container {
    background-color: #303030;
}

.footer-down {
    max-width: 80%;
    margin: auto;
    padding: 15px 0;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.bttn {
    padding: 10px;
    color: white;
    border: 2px solid #0282f9;
}

.social {
    display: flex;
    justify-content: center;
    align-items: center;
}

.social span {
    font-weight: 800;
    font-size: 18px;
    color: #0282f9;
}

.social>img {
    padding-left: 15px;
}
</style>