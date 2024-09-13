<script>
    export default {
        data() {
            return {
            };
        }
    }
</script>


<template>
    <div class="container bg-image">
        <div class="container-ul centered">
            <div class="double-column">
                <div class="titolo">
                    DC Comics
                </div>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <div>
                    <div class="titolo">
                        SHOP
                    </div>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
            </div>
            <div>
                <div class="titolo">
                    DC
                </div>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <div>
                <div class="titolo">
                    SITES
                </div>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .bg-image {
        background-image: url("/vue-dc-comics-1/img/footer-bg.jpg");
    }

    .container {
        padding-top: 30px;
        padding-bottom: 30px;
        min-height: 400px;
    }

    .titolo {
        color: white;
        font-weight: bold;
        /* Puoi aggiungere altri stili qui */
    }

    ul {
        color: grey;
        list-style-type: none;
        /* Rimuove i pallini */
    }

    ul>li {
        text-decoration-style: none;
    }
</style>

<style scoped>
    .bg-image {
        background-image: url("/vue-dc-comics-1/img/footer-bg.jpg");
    }

    .container {
        padding-top: 30px;
        padding-bottom: 30px;
        min-height: 400px;
    }

    .titolo {
        color: white;
        font-size: 25px;
        margin-bottom: 20px;

    }

    ul {
        color: grey;
        padding: 0;
        text-decoration-style: none;
    }

    ul>li {
        margin-bottom: 10px;
    }

    .container-ul {
        display: flex;
        gap: 30px;
    }

    .double-column {}
</style>
