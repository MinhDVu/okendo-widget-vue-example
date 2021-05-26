<template>
    <div class="page-wrapper">
        <h1>Minh's Meaty Meat Pies</h1>
        <OkendoReviewsWidget :productId=bar :enableFilters=foo />
    </div>
</template>

<script>
import { OkendoReviewsWidget } from '@okendo/okendo-widgets-vue';

export default {
    name: 'HelloWorld',
    components: {
        OkendoReviewsWidget
    },
    data () {
        return {
            foo: false,
            bar: 'shopify-1596736602164'
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
