<script>
import MainMenu from "./MainMenu.vue"
export default {
    components: {
        MainMenu
    }
}
</script>

<template>
    <div class="background">
        <div class="container">
            <div class="content">
                <h1>Content goes here</h1>
            </div>
        </div>
    </div>
    <MainMenu />
</template>

<style scoped>
h1 {
    color: white;
}

.background {
    background-color: #1c1c1c;
}

.content {
    display: flex;
    align-items: center;
    height: 150px;
}
</style>