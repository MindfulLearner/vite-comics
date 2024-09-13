<script>
    import Header from './components/Header.vue';
    import JumboTron from './components/JumboTron.vue';
    import CardList from './components/CardList.vue';
    import BlueStripe from './components/BlueStripe.vue';
    import Footer from './components/Footer.vue';
    import SottoFooter from './components/SottoFooter.vue';
    export default {
        data() {
            return {
            };
        },
        components: {
            Header,
            JumboTron,
            CardList,
            BlueStripe,
            Footer,
            SottoFooter
        }
    };
</script>

<template>
    <!-- caricato header -->
    <Header />
    <!-- jumbotron -->
    <JumboTron />
    <!-- card jumbo -->
    <CardList />
    <!-- blu pert -->
    <BlueStripe />
    <!-- Footer -->
    <Footer />
    <!-- SottoFooter -->
    <SottoFooter />

</template>

<style scoped>
</style>
