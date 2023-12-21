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
        <HeaderNav></HeaderNav>
        <div class="container">
            <img src="../../public/img/h3-rev-img-6.png" alt="">
        </div>

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
</style>
