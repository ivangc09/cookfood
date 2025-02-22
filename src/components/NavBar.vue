<script>
    import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
    import { faSearch } from '@fortawesome/free-solid-svg-icons';

    export default {
        components: {
            FontAwesomeIcon,
        },
        data(){
            return{
                searchIcon: faSearch,
            }
        }
    };
</script>

<template>
    <nav>
        <ul>
            <li>Main Meals</li>
            <li>Entertaining</li>
            <li>Puddings</li>
            <li>Meal Boxes</li>
            <li>Offers</li>
            <li>Gifts</li>
            <li>About us</li>
        </ul>

        <input type="text" placeholder="Search our Frozen Meals and Puddings">
        </input>
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

ul{
    display: flex;
    justify-content: space-between; 
    gap: 20px;
    color: white;
    font-family:'Fira Sans';
    list-style: none;
}

input{
    border-radius: 10px;
    border: solid 1px #235556;
    width: 300px;
    margin: 5px;
}
</style>