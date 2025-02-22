<script>
    export default {
        props: {
            imageUrl1: 'foodcook/cook.jpg',
            imageUrl2: '/chef.jpg'
        }
    }
</script>

<template>

    <div class="find-cook">
        <div class="find-cook-container">
            <img :src="imageUrl1" alt="food" />
            <div class="text">
                <h2>Find COOK Near You</h2>
                <p>We're on highstreets.</p>
                <p>Pop-in for a warm welcome and free taster,</p>
                <p>of find a stocksit near you</p>
                
            </div>
            <img :src="imageUrl2" alt="chef" />
        </div>
    </div>
</template>

<style scoped>
.find-cook-container{
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #ffd843;
    padding: 30px;
}

.find-cook img{
    width: 400px;
    height: 350px;
}

.text{
    font-family: 'HugosHandTwo';
    font-size: 20px;
    text-align: center;
    color: #4c5f34;
}

</style>