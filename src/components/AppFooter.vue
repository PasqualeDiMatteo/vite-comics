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
<style scoped>
footer {
    background-color: #303030;
    height: 94px;
}

.footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
}

.social-icon {
    display: flex;
    align-items: center;
}

button {
    background-color: inherit;
    border: 1px solid #0282f9;
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
    color: #0282f9;
    margin-right: 20px;
    font-weight: 600;
}
</style>