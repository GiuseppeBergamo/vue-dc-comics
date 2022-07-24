<template>
  <nav class="header-nav container">
    <div>
        <img src="../assets/img/dc-logo.png" alt="dc-logo">
    </div>
    <div class="link-container">
        <ul class="link-list">
            <li v-for="link in links" :key="link.text" :class="{'active' : link.current}"> 
                <a :href="link.url">{{ link.text.toUpperCase() }}</a>
            </li>
        </ul>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'BaseHeader',
    data() {
        return {
            links: [
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

<style>
    .header-nav {
        height: 110px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .link-container{
        height: 100%;
    }

    .link-list{
        list-style-type: none;
        display: flex;
        align-items: center;
        height: 100%;
    }
    
    .link-list li{
        margin-left: 10px;
        margin-right: 10px;
        cursor: pointer;
        height: 100%;
        display: flex;
        align-items: center;
    }

    .link-list li.active{
        border-bottom: 2px solid #0282f9;

    }

    .link-list li.active a{
        color: #0282f9;
    }

    .link-list a{
        font-weight: 600;
    }
</style>