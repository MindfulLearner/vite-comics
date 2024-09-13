<script>
    export default {
        data() {
            return {
            };
        }
    }
</script>


<template>
    <div class="bg-color">
        <div class="centered container">
            <div class="sign-box">
                SIGN-UP NOW!
            </div>
            <div class="follow-box">
                <div>
                    FOLLOW US
                </div>
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/footer-facebook.png" alt="">
                </div>
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/footer-twitter.png" alt="">
                </div>
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/footer-youtube.png" alt="">
                </div>
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/footer-pinterest.png" alt="">
                </div>
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>


<style scoped>
    .bg-color {
        background-color: rgb(28, 28, 28);
    }

    .container {
        display: flex;
        height: 100px;
        justify-content: space-between;
        align-items: center;
        text-align: center;
        padding-right: 20px;
        color: white;
        padding-left: 20px;
    }

    .sign-box {
        width: 200px;
        height: 40px;
        outline: 2px blue solid;
        align-content: center;
        align-items: center;
        text-align: center;
    }

    .follow-box {
        display: flex;
        align-content: center;
        align-items: center;
        text-align: center;
        gap: 10px;
    }

    .img-container {
        width: 30px;
        height: 30px;
    }

    img {
        width: 100%;
        height: 100%;
    }
</style>
