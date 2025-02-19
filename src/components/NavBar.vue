<script setup>

</script>

<template>
    <nav>
        <li>
            <ul>Main Meals</ul>
            <ul>Entertaining</ul>
            <ul>Puddings</ul>
            <ul>Meal Boxes</ul>
            <ul>Offers</ul>
            <ul>Gifts</ul>
            <ul>About us</ul>
        </li>

        <input type="text" placeholder="Search our Frozen Meals and Puddings">
    </nav>
</template>

<style scoped>
nav{
    margin: 0;
    display: flex;
    justify-content: space-around;
    gap: 80px;
    background-color: #235556;
}

li{
    display: flex; 
    color: white;
    font-family:'Fira Sans';
}

input{
    border-radius: 10px;
    border: solid 1px #235556;
    width: 300px;
}
</style>