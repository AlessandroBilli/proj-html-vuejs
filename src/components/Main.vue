<script>

import PizzaSection from './PizzaSection.vue';
export default {

};
</script>

<template>
    <div>
        <PizzaSection></PizzaSection>
        <h1 class="text-container">The best pizza Menu </h1>
        <div class="pizza-container">

            <img src="../../public/img/h3-product-img-1a-100x100.png" alt="">
            <img src="../../public/img/h3-product-img-2a-150x150.png" alt="">
            <img src="../../public/img/h3-product-img-3a-150x150.png" alt="">
            <img src="../../public/img/h3-product-img-4a-150x150.png" alt="">
            <img src="../../public/img/h3-product-img-5a-150x150.png" alt="">
            <img src="../../public/img/h3-product-img-6a-100x100.png" alt="">

        </div>
    </div>
</template>

<style>
.text-container {
    display: flex;
    justify-content: center;
    margin-bottom: 100px;
}

.pizza-container {
    width: 100vw;
    display: flex;
    justify-content: space-between;
    background-image: url('../../public/img/h3-rev-img-3.png');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center center;
}

img {
    width: 100%;
}
</style>
