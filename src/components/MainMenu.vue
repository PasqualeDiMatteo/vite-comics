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
<style  scoped>
.main-links {
    background-color: #0282f9;

}

img {
    width: 60px;
    margin-right: 10px;
}

ul {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 150px;
}

a {
    padding: 0 40px;
    display: flex;
    align-items: center;
    font-size: 0.8rem;
    color: white;
}
</style>