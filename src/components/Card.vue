<script>
    export default{
        props: {
            imageUrl: '/cookfood/platillo1.jpg',
            description: String
        }
    }
</script>

<template>
    <div class="card">
        <img :src="imageUrl" alt="food" />

        <div class="overlay">
            <p>{{ description }}</p>
        </div>
    </div>

    
</template>

<style scoped>
.card img{
    width: 400px;
    height: 350px;
}

.overlay p{
    font-family:'Fira Sans';
    font-size: 30px;
    color: #45583e;
}
</style>

