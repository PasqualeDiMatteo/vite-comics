<script>
export default {
    props: {
        image: String,
        title: String
    }
}
</script>

<template>
    <div class="card">
        <img :src=this.image :alt=this.title>
        <h3>{{ this.title }}</h3>
    </div>
</template>
<style scoped lang="scss">
.card {
    flex-basis: calc(100%/6);
    margin: 30px 0;

    img {
        display: block;
        object-fit: scale-down;
        object-position: top;
        width: 100%;
        height: 150px;
        clip-path: inset(0 26% 0 26%);
        cursor: pointer;
    }

    h3 {
        margin-top: 10px;
        margin-left: 26%;
        color: white;
        font-size: 12px;
    }
}
</style>