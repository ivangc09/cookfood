<script setup>
import NavBar from './components/NavBar.vue';
import BackgroundCard from './components/BackgroundCard.vue';
import LogoHeader from './components/LogoHeader.vue';
import Card from './components/Card.vue';
import FindCook from './components/FindCook.vue';
import Footer from './components/Footer.vue';

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

    <Card
      image-url="/offer.jpg"
      description="This Week's Offers"
    />
    <Card
      image-url="/platillo2.jpg"
      description="Low Calorie Meals" 
    />
  </div>

  <FindCook
    image-url1="/cook.jpg"
    image-url2="/chef.jpg"
  />

  <Footer
  
  />
  </main>
</template>

<style scoped>
.cards-container{
  margin: 30px;
  display: flex;
  justify-content: center;
  text-align: center;
  gap: 35px;
}
</style>
