<script>
export default {

}
</script>
<template>
    <footer>
        <div class="container">
            <div class="footer">
                <button>SIGN-UP NOW!</button>
                <div class="social-icon">
                    <span>FOLLOW US</span>
                    <ul>
                        <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                        <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                        <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                        <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                        <li><img src="../assets/img/footer-periscope.png" alt=""></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<style scoped lang="scss">
@use "../assets/scss/_vars.scss" as *;
@use "../assets/scss/_mixins.scss" as *;


footer {
    background-color: $grey;
    height: 94px;
}

.footer {
    @include flexbox(space-between, center);
    height: 100%;
}

.social-icon {
    @include flexbox(flex-start, center);
}

button {
    background-color: inherit;
    border: 1px solid $blue;
    padding: 10px 20px;
    color: white;
    font-weight: 600;
    cursor: pointer;
}

ul {
    display: flex;
}

li {
    padding: 10px;
}

.container {
    height: 100%;
}

span {
    color: $blue;
    margin-right: 20px;
    font-weight: 600;
}
</style>