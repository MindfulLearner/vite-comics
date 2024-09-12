<script>
    import Header from './components/Header.vue';
    import SottoHeader from './components/SottoHeader.vue';
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
            SottoHeader,
            BlueStripe,
            Footer,
            SottoFooter
        }
    };
</script>

<template>
    <!-- caricato header -->
    <Header />
    <!-- sottoheader -->
    <SottoHeader />
    <!-- blu part -->
    <BlueStripe />
    <!-- Footer -->
    <Footer />
    <!-- SottoFooter -->
    <SottoFooter />

</template>

<style scoped>
</style>
