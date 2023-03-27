<script></script>

<template>
    <div class="footer-container debug">
        <div class="footer-top-container">
            <div class="footer-top">
                <div class="links-container">
                    <div class="left-links"></div>
                    <div class="center-links"></div>
                    <div class="right-links"></div>
                </div>
            </div>
        </div>

        <div class="footer-down-container">
            <div class="footer-down">
                <div>BUTTON</div>
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
    max-width: 60%;
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