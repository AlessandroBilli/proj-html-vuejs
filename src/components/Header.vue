<script>
import HeaderNav from './HeaderNav.vue';

export default {
    data() {
        return {};
    },
    components: {
        HeaderNav,

    },





};
</script>

<template>
    <header>
        <a href="#" class="prev">Prev</a>
        <HeaderNav></HeaderNav>
        <div class="container">
            <img src="../../public/img/h3-rev-img-6.png" alt="">
        </div>
        <a href="#" class="next">Next</a>

    </header>
    <div>

    </div>
</template>

<style scoped>
header {
    background-color: #1b1b1b;
    max-width: 125rem;
    max-height: 43.75rem;
    background-image: url('../../public/img/h3-rev-img-5.png');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center center
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
}

img {
    max-height: 450px;
    max-width: 350px;
}

.prev,
.next {
    position: absolute;
    top: 20%;
    transform: translateY(-50%);
    padding: 20px 17px;
    background-color: #ccc;
    background-color: white;
    text-decoration: none;
    color: #da684d;
    border-radius: 22px;



}

.prev {
    left: 0;
    writing-mode: vertical-lr;
    /* Questa proprietà imposta la scrittura in verticale */
    text-orientation: mixed;
    /* Orientamento del testo */
    transform: rotate(0deg);
    left: -1%;
}

.next {
    right: 0;
    writing-mode: vertical-lr;
    /* Questa proprietà imposta la scrittura in verticale */
    text-orientation: mixed;
    /* Orientamento del testo */
    transform: rotate(180deg);
    right: -1%;
}
</style>
