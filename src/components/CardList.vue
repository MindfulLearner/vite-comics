<script>
    export default {
        data() {
            return {
                cards: [
                    {
                        "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                        "price": "$19.99",
                        "series": "Action Comics",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                        "price": "$3.99",
                        "series": "American Vampire 1976",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                        "price": "$16.99",
                        "series": "Aquaman",
                        "type": "graphic novel"
                    },
                    {
                        "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                        "price": "$2.99",
                        "series": "Batgirl",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                        "price": "$3.99",
                        "series": "Batman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg/revision/latest?cb=20080809201655",
                        "price": "$2.99",
                        "series": "Batman Beyond",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg/revision/latest/scale-to-width-down/1200?cb=20130627211607",
                        "price": "$3.99",
                        "series": "Batman/Superman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg/revision/latest?cb=20200929145132",
                        "price": "$4.99",
                        "series": "Batman/Superman Annual",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg/revision/latest?cb=20200929124651",
                        "price": "$5.99",
                        "series": "Batman: The Joker War Zone",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg/revision/latest?cb=20201123054610",
                        "price": "$6.99",
                        "series": "Batman: Three Jokers",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg/revision/latest?cb=20201124094800",
                        "price": "$4.99",
                        "series": "Batman: White Knight Presents: Harley Quinn",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg/revision/latest?cb=20160303223223",
                        "price": "$16.99",
                        "series": "Catwoman",
                        "type": "graphic novel"
                    }
                ]
            };
        }
    };

</script>


<template>
    <div class="container bg-for-card-list">
        <div class="centered">
            <div class="current-series">
                Current Series
            </div>
            <div class="card-container">
                <div v-for="(card, i) in cards" :key="i" class="card-container-for">
                    <div class="card">
                        <img :src="cards[i].thumb" alt="">
                    </div>
                    <div>
                        {{ cards[i].series }}
                    </div>
                </div>
            </div>
            <div class="load-more">
                Load More
            </div>
        </div>
    </div>
</template>


<style scoped>
    .container {
        min-height: 500px;
        position: relative;
        padding-bottom: 20px;
        color: white;
    }

    .bg-for-card-list {
        background-color: rgb(28, 28, 28);
    }

    .current-series {
        position: absolute;
        top: -25px;
        color: white;
        align-content: center;
        text-align: center;
        font-size: 20px;
        height: 50px;
        width: 250px;
        background-color: rgb(2, 130, 249);
    }


    .card-container {
        display: flex;
        padding-top: 50px;
        width: 100%;
        flex-wrap: wrap;
    }

    .card-container-for {
        width: calc((100% / 6) - 20px);
        margin: 10px;

    }

    .card {
        aspect-ratio: 1 / 1;
    }

    img {
        height: 100%;
        width: 100%;
    }

    .load-more {
        margin: 0 auto;
        color: white;
        align-content: center;
        text-align: center;
        font-size: 20px;
        height: 50px;
        width: 250px;
        background-color: rgb(2, 130, 249);
    }
</style>
