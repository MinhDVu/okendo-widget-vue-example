<template>
    <div class="page-wrapper">
        <h1>Minh's Meaty Meat Pies</h1>
        <OkendoCombinedWidget :productId=bar />
    </div>
</template>

<script>
import { OkendoCombinedWidget } from '@okendo/okendo-widgets-vue';

export default {
    name: 'HelloWorld',
    components: {
        OkendoCombinedWidget
    },
    data () {
        return {
            bar: 'shopify-3938292793441'
        }
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import '~@okendo/okendo-widgets-vue/dist/css/main.min.css';
h1 {
    text-align: center;
}

.page-wrapper {
    max-width: 1200px;
    margin: auto;
    padding: 0 20px;
}
</style>
