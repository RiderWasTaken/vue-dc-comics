<template>
    <div class="header-box">
        <div class="top-logo-box"><img src="../assets/img/dc-logo.png" alt=""></div>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
    .header-box {
        justify-content: space-around;
        align-items: center;
        background: #FFF;
        display: flex;
        height: 150px;

    }
    nav ul {
        justify-content: space-around;
        font-weight: 600;
        list-style: none;
        color: #000;
        display: flex;
    }
    nav ul li {
        margin-right: 25px;
    }
</style>