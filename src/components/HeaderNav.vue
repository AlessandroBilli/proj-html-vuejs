<script>
export default {
    name: 'Nav',
    data() {
        return {
            categories: [
                { text: 'Home' },
                { text: 'Pages' },
                { text: 'Menu' },
                { img: '/img/h5-logo-divided-header.png' }, // Percorso dalla radice
                { text: 'Event' },
                { text: 'Blog' },
                { text: 'Landing' },
                { text: 'Cart' },
                { text: 'Search' },
            ],
        };
    },
};
</script>

<template>
    <div>
        <div class="header-container">

            <ul class="header-section ">
                <button class="botton-standard-red">ORDER ONLINE</button>
                <li v-for="(category, index) in categories" :key="index"
                    :class="{ 'move-right': index === 7 || index === 8 }">
                    <template v-if="category.text">
                        <a>{{ category.text }}</a>
                    </template>
                    <template v-else>
                        <div class="image-container">
                            <img :src="category.img" alt="Category Image" class="centered-image" />
                        </div>
                    </template>
                </li>
            </ul>
        </div>

    </div>
</template>

<style>
.header-container {
    display: flex;
    justify-content: center;
    padding: 10px;
    background-color: black;
}

img {
    max-width: 100px;
}

.header-section {
    display: flex;
    align-items: center;
    gap: 20px;
}

li {
    list-style-type: none;
    text-transform: uppercase;
}

a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

.botton-standard-red {
    background-color: red;
    margin-right: 8.3125rem;
    margin-top: ;
    padding: 5px;
    color: white;
    height: 2.5rem;
    width: 8.125rem;
}
</style>
