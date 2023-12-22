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
        <div class="contacts">
            <h1>Lista Contatti Pizzeria</h1>
            <ul>
                <li>
                    <span class="contact-name">Pizzeria Don Peppe</span>
                    <span class="contact-info">Via Roma, 123 - 00100, Città</span>
                    <span class="contact-info">Telefono: 062-3456789</span>
                    <span class="contact-info">Email: info@pizzeriadonpeppe.com</span>
                </li>


            </ul>
        </div>
    </div>
</template>

<style>
.text-container {
    display: flex;
    justify-content: center;
    margin-bottom: 100px;
    font-family: Arial, sans-serif;
    font-weight: bold;

    ;
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


body,
h1,
ul,
li {
    margin: 0;
    padding: 0;
}


.contacts {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    font-family: Arial, sans-serif;
}


h1 {
    text-align: center;
    margin-bottom: 20px;
}


ul {
    list-style-type: none;
}


li {
    border-bottom: 1px solid #ccc;
    padding: 10px 0;
}


.contact-name {
    font-weight: bold;
    font-size: 18px;
}


.contact-info {
    display: block;
    font-size: 14px;
    color: #555;
    margin-top: 5px;
}
</style>
