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
        <div class="container">
            <div class="content">
                <h1>Content goes here</h1>
            </div>
        </div>
    </div>
    <MainMenu />
    <MainSection />
</template>

<style scoped lang="scss">
@use "../assets/scss/_vars.scss" as *;
@use "../assets/scss/_mixins.scss" as *;


h1 {
    color: white;
}

.background {
    background-color: $dark-gray;
}

.content {
    @include flexbox(flex-start, center);
    height: 150px;
}
</style>