<template>
  <nav class="navbar_container">
    <div>
          <img class="bilka_logo_container" alt="bilka logo" src="./assets/bilka_logo.png">
    </div>
    <div>
      <select class="language_icon_container" name="languages" id="languages">
        <option value="Danish">Danish</option>
        <option value="English">English</option>
        <option value="German">German</option>
      </select>
    </div>
    <div class="right_end_navbar">
      <a class="assistance_button">
        Assistance
      </a>
    </div>
  </nav>

  <section class="section_frame">
    <button to="/about" class="startscan_icon">Start</button>
    <div>
      <button class="ownpackage_icon">Egen Pose</button>
      <button class="newsletter_icon">Nyhedsavis</button>
    </div>
  </section>

  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.navbar_container{
  background: #00b3ff;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  display: flex;
  flex-direction: row;
  height: 60px;
}

.bilka_logo_container{
  height: 40px;
  margin-left: 10px;
  margin-top: 10px;
}

.language_icon_container{
  display: flex;
  align-items: center;
  text-align: center;
  justify-content: center;
  height: 40px;
  width: 100px;
  margin-left: 20px;
  margin-top: 10px;
  border: solid;
  border-radius: 5%;
  background: #00b3ff;
  color: #ffff;
  border-color: #ffff;
}

.assistance_button{
  display: flex;
  align-items: center;
  justify-content: center;
  height: 40px;
  width: 100px;
  margin-left: 20px;
  margin-top: 7px;
  margin-bottom: 3px;
  border: solid;
  border-radius: 5%;
  background: #00b3ff;
  color: #ffff;
  border-color: #ffff;
}

.right_end_navbar{
  margin-left: 73%;
}

.section_frame{
  margin-top: 10%;
  margin-left: 25%;
  width: 50%;
  height: 50%;
  border: 1px white solid;
  flex-direction: column;
}

.startscan_icon{
  width: 500px;
  height: 250px;
  background-color: #00b3ff;
  margin-bottom: 5%;
  color: white;
  font-weight: bolder;
  font-size: 100px;
  border-radius: 25px;
}

.ownpackage_icon{
  width: 200px;
  height: 150px;
  background-color: #00b3ff;
  color: white;
  font-weight: bolder;
  font-size: 25px;
  border-radius: 25px;
}

.newsletter_icon{
  width: 200px;
  height: 150px;
  background-color: #00b3ff;
  color: white;
  font-weight: bolder;
  font-size: 25px;
  margin-left: 10%;
  border-radius: 25px;
}

.barcode_logo_container{
  height: 40px;
  margin-left: 10px;
  margin-top: 10px;
}

</style>
<script setup lang="ts">
</script>

<!--    <router-link to="/">Home</router-link> |-->
<!--    <router-link to="/about">About</router-link>-->