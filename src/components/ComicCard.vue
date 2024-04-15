<script>
export default {
    name: 'ComicCard',
    props: ['cardInfo']
}
</script>

<template>
    <div class="comic-card">
        <div>
            <img :src="cardInfo.thumb">
        </div>
        <div>
            <h3>{{ cardInfo.series }}</h3>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    .comic-card {
        width: calc(100% / 6);
        padding-bottom: 20px;

        img {
            height: 150px;
            width: 150px;
            object-fit: fill;
        }

        h3 {
            color: white;
            width: 150px;
            padding-top: 10px;
        }
    }
</style>