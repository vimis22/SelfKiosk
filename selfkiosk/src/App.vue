<template>
  <nav class="navbarframe">
    <marquee class="marquee">
      <img class="bilka_logo" alt="bilka logo" src="./assets/bilka_logo.png">
      <img class="bilka_logo" alt="bilka logo" src="./assets/sallinggroup_logo.png">
      <img class="bilka_logo" alt="bilka logo" src="./assets/br_logo.png">
      <img class="bilka_logo" alt="bilka logo" src="./assets/carlsjr_logo.png">
      <img class="bilka_logo" alt="bilka logo" src="./assets/netto_logo.png">
      <img class="bilka_logo" alt="bilka logo" src="./assets/fotex_logo.png">
      <img class="bilka_logo" alt="bilka logo" src="./assets/starbucks_logo.png">
      <!--    <router-link to="/">Home</router-link> |-->
      <!--    <router-link to="/about">About</router-link>-->
    </marquee>
    <div class="payment_info">
      Accepts only Cash and Card
    </div>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffff;
}

.navbarframe{
  flex-direction: row;
  display: flex
}

.marquee{
  background-color: #82c8ff;
  color: white;
  height: 50px;
  width: 75%;
  margin-right: 10px;
}

.payment_info{
  background-color: #00e362;
  color: white;
  height: 50px;
  width: 18%;
  text-align: center;
  justify-content: center;
}

.bilka_logo{
  height: 50px;
  margin-left: 10px;
}
</style>
<script setup lang="ts">
</script>