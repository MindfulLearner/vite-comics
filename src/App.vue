<script>
    import Header from './components/Header.vue';
    export default {
        data() {
            return {
                messaggio: "cacc",
            };
        },
        components: {
            Header
        },
        methods: {
            swagTasto() {
                console.log('like');
            }
        }
    };
</script>

<template>
    <Header />
    <div>
        <h1>
            {{ messaggio }}
        </h1>
    </div>
</template>

<style scoped>
    h1 {
        color: white;
    }
</style>
