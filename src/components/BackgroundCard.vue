<template>
    <div 
        class="background-card"
        :style="{ backgroundImage: `url(${imageUrl})` }"
    >
        <div class="overlay">
            <h1>{{ title }}</h1>
            <p>{{ description }}</p>
        </div>
    </div>
</template>

<script>

export default {
    props: {
        imageUrl: String,
        title: String,
        description:String
    }
};
</script>

<style scoped>
.background-card {
    width: 100%;
    height: 500px;
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: left;
    color: #163134;
    font-family:'HugosHandTwo';
    font-size: 25px;
    position: relative;
}

.background-card {
    background-image: v-bind('`url(${imageUrl})`');
}
.overlay{
    width: 30%;
    padding-left: 50px;
}

.overlay p{
    font-family: 'Inter Regular';
}

</style>