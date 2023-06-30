<script>
import MainMenu from "./MainMenu.vue"
import MainSection from "./MainSection.vue"
import ComicCard from "./ComicCard.vue"


export default {
    props: {
        books: Array
    },
    components: {
        MainMenu,
        MainSection,
        ComicCard
    }
}
</script>

<template>
    <div class="background">

        <div class="jumbotron">
            <img src="../assets/img/jumbotron.jpg" alt="">
        </div>
        <div class="container container-card">
            <div class="series">CURRENT SERIES</div>
            <div class="content">
                <ComicCard v-for="book in books" :image=book.thumb :title=book.series />
            </div>
            <button>LOAD MORE</button>
        </div>
    </div>
    <MainMenu />
    <MainSection />
</template>

<style scoped lang="scss">
@use "../assets/scss/_vars.scss" as *;
@use "../assets/scss/_mixins.scss" as *;



.container-card {
    padding-bottom: 30px;
    position: relative;
}

.series {
    color: white;
    padding: 10px 20px;
    background-color: $blue;
    position: absolute;
    top: 0;
    left: 25px;
    transform: translateY(-50%);
}

.jumbotron {
    max-width: 100%;
    height: 400px;

    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
    }
}

.background {
    background-color: $dark-gray;
}

.content {
    @include flexbox(start, start, wrap);
}

button {
    display: block;
    margin: 0 auto;
    background-color: $blue;
    color: white;
    border: 0;
    padding: 10px 20px;
    cursor: pointer;
}
</style>