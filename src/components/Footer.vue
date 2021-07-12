<template>
    <div class="footer-box">
        <div class="top-footer">
            <div class="footer-lists-box">
                <ul> 
                    <h3>DC COMICS</h3>
                    <li>Character</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <h3>DC</h3>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (new)</li>
                    <li>Ad Choices</li>
                    <li>Advertasing</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Telnt Workshop</li>
                    <li>CPSP Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
                <ul>
                    <h3>SITES</h3>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power visa</li>

                </ul>
                <ul>
                    <h3>SHOP</h3>
                    <li>Shop DC</li>
                    <li>Shop Dc Collectibles</li>
                </ul>
            </div>
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
        <div class="bottom-footer-box">
            <button>SIGN-UP NOW! </button>
            <div>
                <span>FOLLOW US</span>
                <div>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
    .footer-box {
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
    }

    .top-footer {
        display: flex;
        justify-content: space-around;

    }

    .footer-lists-box {
        display: flex;
        flex-wrap: wrap;
    }
    .footer-lists-box ul{
        list-style: none;
        color: #FFF;

    }
    .bottom-footer-box {
        background: #303030;
        z-index: 9999;
        height: 100px;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-around;
        padding: 25px;
    }

    .bottom-footer-box div {
        display: flex;
        align-items: center;
        justify-content: space-around;
    }
</style>