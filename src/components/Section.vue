<template>
    <div class="main-box">
        <div class="main"><h1>--> Content goes here :) </h1></div>
        <div class="shop-nav">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span> SUBSCRIPTION</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC POWER VISA</span>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Main'
}
</script>

<style lang="scss" scoped>
    .main-box {
        height: 350px;
    }

    .main {
        height: 150px;
        background: #1C1C1C;
        display: flex;
        justify-content: center;
        align-items: center;
        color: #FFF;
    }

    .shop-nav {
        height: 200px;
        background: #0282F9;
        color: white;
        padding: 15px;
        justify-content: space-between;
    }

    .shop-nav ul {
        display: flex;
        list-style: none;
        justify-content: space-around;
        
    }

    .shop-nav ul li {
        display: flex;
        align-items: center;
    }
</style> 