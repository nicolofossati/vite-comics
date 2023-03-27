<script></script>

<template>
    <div class="header-container debug">
        <div class="header-content">
            <img src="../img/dc-logo.png" alt="logo-dc">
            <div class="nav-bar">
                <ul>
                    <li><a href="">ONE</a></li>
                    <li><a href="">TWO</a></li>
                    <li><a href="">THREE</a></li>
                    <li><a href="">FOUR</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
.header-container {}

.header-content {
    display: flex;
    justify-content: space-between;
    max-width: 60%;
    margin: auto;
}

.header-content>img {
    width: 80px;
    padding: 10px;
}

.nav-bar ul {
    display: flex;
    flex-direction: row;
    padding: 0;
}

ul li {
    list-style-type: none;
    padding: 10px;
}
</style>