<template>
    <div id="app">
        <HelloWorld />
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import { configureOkendo } from '@okendo/okendo-widgets-vue';

configureOkendo({
    subscriberId: '20d7b234-9bce-4735-a606-ac6d673a91a9',
    widgetSettings: {
        dateFormat: 'MMM/d/yyyy',
        enableFilters: true,
        defaultReviewsSortOrder: 'rating asc'
    }
});
export default {
    name: 'App',
    components: {
        HelloWorld
    }
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
