<script>
import MainMenu from "./MainMenu.vue"
import MainSection from "./MainSection.vue"

export default {
    components: {
        MainMenu,
        MainSection
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
                <div class="card">
                    <img src='https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY'
                        alt="">
                    <h3>Action Comics</h3>
                </div>
                <div class="card">
                    <img src='https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY'
                        alt="">
                    <h3>Action Comics</h3>
                </div>
                <div class="card">
                    <img src='https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY'
                        alt="">
                    <h3>Action Comics</h3>
                </div>
                <div class="card">
                    <img src='https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY'
                        alt="">
                    <h3>Action Comics</h3>
                </div>
                <div class="card">
                    <img src='https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY'
                        alt="">
                    <h3>Action Comics</h3>
                </div>
                <div class="card">
                    <img src='https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY'
                        alt="">
                    <h3>Action Comics</h3>
                </div>
                <div class="card">
                    <img src='https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY'
                        alt="">
                    <h3>Action Comics</h3>
                </div>
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


h1 {
    color: white;
}

.background {
    background-color: $dark-gray;
}

.content {
    display: flex;
    flex-wrap: wrap;
}

.card {
    flex-basis: calc(100%/6);
    margin: 30px 0;


    img {
        display: block;
        object-fit: cover;
        width: 100%;
        height: 150px;
        clip-path: inset(0 17% 0 17%);
    }

    h3 {
        margin-top: 10px;
        margin-left: 17%;
        color: white;
        font-size: 15px;
    }
}

button {
    display: block;
    margin: 0 auto;
    background-color: $blue;
    color: white;
    border: 0;
    padding: 10px 20px;
}
</style>