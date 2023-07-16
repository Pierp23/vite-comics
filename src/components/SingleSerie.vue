<script>
export default {
    name: "MainComponent",
    props: {
        serieImg: String,
        serieTitle: String
    },

}
</script>

<template>
    <div class="card">
        <div>
            <img :src="serieImg" :alt="serieTitle">
        </div>
        <h3>
            {{ serieTitle }}
        </h3>
    </div>
</template>

<style lang="scss" scoped>
.card {
    color: white;
    width: calc(100% / 6 - 10px);
    padding: 5px;
    margin-bottom: 50px;

    &:hover {
        cursor: pointer;
        transform: scale(105%);
    }

    &:hover div {
        opacity: 0.5;
    }

    div {
        width: 150px;
        height: 150px;
    }

    div img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
    }

    h3 {
        text-align: left;
        margin-top: 10px;
    }
}
</style>
