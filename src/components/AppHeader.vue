<script>
export default {
    data() {
        return {
            navbar: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ],
        }
    }
}
</script>

<template>
    <header>
        <div class="container">
            <div class="nav-bar">
                <figure>
                    <img src="../assets/img/dc-logo.png" alt="DC Logo">
                </figure>
                <nav>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>

<style scoped>
.nav-bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;
}

a {
    color: black;
}
</style>
