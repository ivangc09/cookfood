<script>
    import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
    import { faUser } from '@fortawesome/free-solid-svg-icons';

    export default {
        components: {
            FontAwesomeIcon,
        },
        props: {
            imageUrl: String,
        },
        data(){
            return{
                userIcon: faUser,
            }
        }
    };
</script>

<template>
    <div class="container">
        <div class="logo-header">
            <img :src="imageUrl" alt="logo" />
        </div>

    </div>
</template>

<style scoped>
.container{
    display: flex;
    justify-content: center;
    align-items: center;
}

.logo-header{
    padding: 20px;
    width: 400px;
}
.icon{
    font-size: 24px;
    color: gray;
}

.icon:hover{
    color: #235556;
}
</style>