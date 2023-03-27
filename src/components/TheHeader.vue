<script></script>

<template>
    <div class="header-container debug">
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
</template>

<style scoped>
/*   DEBUG */
.debug .nav-bar {
    background-color: aqua;
}

/*  FINE DEBUG */
.header-container {
    display: flex;
    justify-content: space-between;
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