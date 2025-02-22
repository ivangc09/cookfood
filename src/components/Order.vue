<script>
    export default{
        props: {
            imageUrl1: String,
        }
    }
</script>

<template>
    <div class="order-container">
        <div class="family">
            <img :src="imageUrl1" alt="family" />
        </div>

        <div class="text">
            <h2>Bringing people together over good food since 1997</h2>
            <ul class="star-list">
                <li>Award-winning meals and puddings</li>
                <li>Hand-prepared by chefs from great ingredients</li>
                <li>Look and taste homemade</li>
                <li>Frozan to lock-in flavour and cut down waste</li>
            </ul>    
        </div>

        
    </div>
</template>

<style>
.order-container{
    background-color: #426261;
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 10px;
    padding: 30px;
}

.family img {
    width: 700px;
    height: 100%;
    object-fit: cover;
}

.text{
    width: 40%;
    color: white;
    font-family: 'Inter Regular';
    font-size: 25px;
    line-height: 2;
}
.star-list
{
    list-style: none;
    padding: 0;
}

.star-list li::before {
    content: '⭐';
    margin-right: 8px;
}
</style>