<template>
    <div id="base-card-container">
        <div id="card" v-for="comic in comics" :key="comic.series">
            <img :src="comic.thumb" :alt="comic.series">
            <p>{{comic.series}}</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BaseCard',
    props: {
        comics: Array
    }
}
</script>

<style>
    #card{
        width: calc(100% / 6);
        height: 300px;
        padding: 40px;
    }
    #card p{
        text-align: center;
        text-transform: uppercase;
    }
    #card img{
        max-width: 100%;
        height: auto;
    }

    #base-card-container{
        display: flex;
        align-items: center;
        flex-wrap: wrap;
    }
</style>