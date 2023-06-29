<script>
export default {
    data() {
        return {
            mainLinks: [
                {
                    text: 'DIGITAL COMICS',
                    url: '#',
                    img: '../assets/img/buy-comics-digital-comics.png',
                },
                {
                    text: 'DC MERCHANDISE',
                    url: '#',
                    img: '../assets/img/buy-comics-merchandise.png',
                },
                {
                    text: 'SUBSCRIPTION',
                    url: '#',
                    img: '../assets/img/buy-comics-subscriptions.png',
                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    url: '#',
                    img: '../assets/img/buy-comics-shop-locator.png',
                },
                {
                    text: 'DC POWER VISA',
                    url: '#',
                    img: '../assets/img/buy-dc-power-visa.svg',
                },
            ]
        }
    },
    methods: {
        getImagePath(img) {
            const url = new URL(`${img}`, import.meta.url)
            return url.href;
        }
    }
}
</script>
<template>
    <div class="main-links">
        <div class="container">
            <ul>
                <li v-for="link in mainLinks">
                    <a :href="link.url">
                        <img :src="getImagePath(link.img)" alt="">
                        <h3>{{ link.text }}</h3>
                    </a>
                </li>
            </ul>
        </div>
    </div>
</template>
<style lang="scss" scoped>
@use "../assets/scss/_vars.scss" as *;
@use "../assets/scss/_mixins.scss" as *;

.main-links {
    background-color: $blue;
}

img {
    width: 60px;
    height: 70px;
    margin-right: 10px;
    object-fit: scale-down;
}

ul {
    @include flexbox(space-between, center);
    width: 100%;
    height: 150px;
}

a {
    padding: 0 40px;
    @include flexbox(flex-start, center);
    font-size: 0.8rem;
    color: white;
}
</style>