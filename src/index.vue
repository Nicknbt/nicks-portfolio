<template>
    <Header />
    <img alt="Vue logo" src="./assets/images/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Footer />
</template>

<script>
import Header from './components/Header.vue';
import HelloWorld from './components/HelloWorld.vue';
import Footer from './components/Footer.vue';

export default {
    name: 'index',
    components: {
        Header,
        HelloWorld,
        Footer,
    },
};
</script>
