<script>
export default {
}
</script>

<template>
    <div class="background">
        <div class="container">
            <div class="list-container">
                <div class="list-item">
                    <h2>DC COMICS</h2>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                        <h2>SHOP</h2>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </ul>
                </div>
                <div class="list-item">
                    <h2>DC</h2>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscription</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CBSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="list-item">
                    <h2>SITES</h2>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.background {
    background: no-repeat 80% 50% /600px url(../assets/img/dc-logo-bg.png), no-repeat center / 2000px url(../assets/img/footer-bg.jpg);
}

h2 {
    color: white;
    padding: 10px 0;
}

a {
    color: gray;
    line-height: 30px;
}

.list-container {
    display: flex;
    padding-bottom: 40px;
}

.list-item {
    margin-right: 50px;
}
</style>