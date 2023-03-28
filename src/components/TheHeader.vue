<script>
export default {
    data() {
        return {
            navBar: [
                {
                    text: "CHARACTERS"
                },
                {
                    text: "COMICS"
                },
                {
                    text: "MOVIES"
                },
                {
                    text: "TV"
                },
                {
                    text: "GAMES"
                },
                {
                    text: "COLLECTIBLES"
                },
                {
                    text: "VIDEOS"
                },
                {
                    text: "FANS"
                },
                {
                    text: "NEWS"
                },
                {
                    text: "SHOP"
                }
            ]
        };
    },
};
</script>

<template>
    <div class="header-container debug">
        <div class="header-content">
            <img src="../img/dc-logo.png" alt="logo-dc">
            <div class="nav-bar">
                <ul>
                    <li v-for="link in navBar"><a href="">{{ link.text }}</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.header-content {
    display: flex;
    justify-content: space-between;
    max-width: 80%;
    margin: auto;
    padding: 15px;

    &>img {
        width: 80px;
    }
}

.nav-bar {
    display: flex;
    align-items: center;

    ul {
        display: flex;
        flex-direction: row;
        padding: 0;

        li {
            list-style-type: none;
            padding-left: 12px;

        }
    }

    a {
        text-decoration: none;
        font-weight: 600;
        color: #565656;
    }
}
</style>