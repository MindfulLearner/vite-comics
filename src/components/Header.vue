<script>
    export default {
        data() {
            return {
                dati: 0,
            }
        }
    }
</script>

<template>
    <div class="wrapper centered">
        <div class="img-container">
            <img src="/vue-dc-comics-1/img/dc-logo.png" alt="">
        </div>
        <div class="swagger">
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
                <li>SHOPS</li>
            </ul>
        </div>
    </div>
</template>

<style scoped>
    img {
        width: 100%;
        height: auto;
    }

    .img-container {
        width: 70px;
        display: flex;
    }

    .wrapper {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100px;
    }


    ul {
        padding: 0;
        display: flex;
        gap: 20px;
    }

    ul>li {
        list-style-type: none;
        font-weight: bold;
    }
</style>
