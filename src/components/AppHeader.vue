<script>
export default {
    data() {
        return {
            navbarLinks: [
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
                    <a href="#"><img src="../assets/img/dc-logo.png" alt="DC Logo"></a>
                </figure>
                <nav>
                    <ul>
                        <li v-for="link in navbarLinks">
                            <a :href="link.url" :class="{ active: link.current }">
                                {{ link.text }}
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use "../assets/scss/_vars.scss" as *;
@use "../assets/scss/_mixins.scss" as *;


.nav-bar {
    @include flexbox(space-between, center);
    height: 120px
}

figure {
    flex-basis: calc(100%/5);
    flex-grow: 0;
    flex-shrink: 0;
    height: 100%;
    @include flexbox(space-between, center);


}

img {
    height: 80px;
    align-items: center;
}

nav {
    flex-basis: calc(100%/5*4);
    flex-grow: 0;
    flex-shrink: 0;
    height: 100%;
    text-align: right;
}

ul {
    display: flex;
    height: 100%;
    justify-content: end;

}

li {
    height: 100%;
    @include flexbox(flex-start, center);
}

a {
    color: black;
    padding: 0px 10px;
    font-size: 0.8rem;
    font-weight: 600;
    text-transform: uppercase;
    display: flex;
    line-height: 120px;
}


.active {
    color: $blue;
    border-bottom: 3px solid $blue;
}
</style>
