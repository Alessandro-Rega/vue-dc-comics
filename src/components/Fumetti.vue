<template>
    <div class="fumetto">
        <div class="immagine">
            <img :src="fumetto.thumb" :alt="fumetto.series">
        </div>
        <span>{{fumetto.series}}</span>
    </div>
</template>

<script>
export default {
    name: 'Fumetti',
    props: {
        fumetto: Object
    }
}
</script>

<style scoped>

.fumetto{
    width: min-content;
    display: flex;
    flex-direction: column;
    margin: 15px;
    cursor: pointer;
}

.immagine{
    height: 190px;
    overflow: hidden;
    transition-duration: 1s;
}

.immagine:hover{
    transform: scale(1.1);
}

span{
    color: white;
    text-transform: uppercase;
    font-size: 14px;
    padding: 15px 0;
}

</style>