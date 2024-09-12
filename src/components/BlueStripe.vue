<script>
    export default {
        data() {
            return {
            };
        }
    }
</script>


<template>
    <div class="container bg-blue">
        <div class="container centered">
            <div class="card">
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="">
                </div>
                <div>
                    DIGITAL COMICS
                </div>
            </div>
            <div class="card">
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/buy-comics-merchandise.png" alt="">
                </div>
                <div>
                    DC MERCHANDISE
                </div>
            </div>
            <div class="card">
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="">
                </div>
                <div>
                    SUBSCRIPTIONS
                </div>
            </div>
            <div class="card">
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="">
                </div>
                <div>
                    COMIC SHOP LOCATOR
                </div>
            </div>
            <div class="card">
                <div class="img-container">
                    <img src="/vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="">
                </div>
                <div>
                    DC POWER VISA
                </div>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
    .bg-blue {
        background-color: rgb(2, 130, 249);
    }

    .container {
        height: 120px;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 10px;
    }

    .img-container {
        height: 60px;
        height: 40px;
        display: flex;
    }

    img {
        width: 100%;
        height: auto;
    }

    .card {
        display: flex;
        align-items: center;
        gap: 15px;
        color: white;
    }
</style>
