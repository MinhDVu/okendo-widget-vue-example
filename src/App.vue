<template>
    <div id="app">
        <HelloWorld />
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import { configureOkendo } from '@okendo/okendo-widgets-vue';

configureOkendo({ subscriberId: '99f886ce-b10d-443a-89c9-e52b83c22d92' });
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
