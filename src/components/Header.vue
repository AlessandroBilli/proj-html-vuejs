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
    <div>
        <HeaderNav></HeaderNav>
    </div>
</template>

<style scoped lang="scss">
.header-container {
    display: flex;
    justify-content: space-around;
    padding: 10px;
    align-items: center;

    img {
        max-width: 100px;
    }

    .header-section {
        display: flex;
        align-items: center;
        gap: 20px;
        margin-left: auto;

        li {
            list-style-type: none;
            text-transform: uppercase;

            a {
                text-decoration: none;
                color: black;
                font-weight: bold;
            }
        }
    }
}
</style>
