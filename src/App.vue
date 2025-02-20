<script setup>
import NavBar from './components/NavBar.vue';
import BackgroundCard from './components/BackgroundCard.vue';
import LogoHeader from './components/LogoHeader.vue';
import Card from './components/Card.vue';

</script>

<template>
  <header>
    <LogoHeader 
      image-url="/logosvg.svg"
    />
  </header>

  <main>
  <NavBar>

  </NavBar>
  <BackgroundCard 
    image-url="/comida.jpg"
    title="Award-Winning Frozen Meals & Puddings"
    description="Home Delivery, free Click & Collect, Subscribe or visit your local COOK Shop or Stockist."
  />

  <div class="cards-container">
    <Card 
    image-url="/platillo1.jpg"
    description="Bestsellers"
    />
  </div>

  </main>
</template>

<style scoped>
.cards-container{
  margin: 30px;
  display: flex;
  justify-content: center;
  text-align: center;
  gap: 10px;
}
</style>
