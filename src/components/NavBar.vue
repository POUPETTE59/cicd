<template>
    <div class="navBar">
      <div class="button">
        <div class="barre barre1"></div>
        <div class="barre barre2"></div>
        <div class="barre barre3">
        </div>
      </div>
      <div class="logo">
        <img class="logoImage" src="../assets/logo.png" alt="" srcset="">
      </div>
      <div class="logoloupe">
        <div class="loupe"></div>
        <div class="zoomedImage">
          <img class="zoomed" src="../assets/table2.jpg" alt="Zoomed Image">
        </div>
      </div>
    </div>
</template>
   
  
<script setup lang="ts">
</script>

<style scoped>
.navBar {
    height : 10vh;
    background-color: #FDF4D1;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.button {
    width : 5vh;
    height : 4vh;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-left: 10px;
}

.barre {
    width : 100%;
    height: 05px;
    background-color: #6C9E41;
    border-radius: 5px;
}

.logo {
    width : 15vh;
    height : 40px;
    position: relative;
    display: flex;
    justify-content: center;
    margin-left: 50px;
} 

.logoImage{
  height: 100%;
}

.logoloupe {
    width : 11vh;
    height : 10vh;
    background-color: #FDF4D1 ;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-left: 10px;
}
.loupe {
    width: 17px;
    height: 17px;
    background-color: #6C9E41; 
    border-radius: 50%; 
    position: relative;
    cursor: pointer;
    box-shadow: 0 0 10px rgba(61, 76, 216, 0.2); 
    z-index: 1;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-top: 20px;
    margin-left: 30px;
}
.loupe::before {
    content: '';
    width: 11px; 
    height: 11px;
    background-color: #FDF4D1;
    border-radius: 50%;
    position: absolute;
    margin-top: 3px;
    margin-left: 3px;
}

.loupe::after {
    content: "";
    width: 11px;
    height: 4px;
    background-color: #6C9E41;
    position: absolute;
    bottom: -5px;
    right: -6px;
    transform: rotate(50deg); 
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.zoomedImage {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    z-index: 0;
    width: 200px;
    height: 200px;
    overflow: hidden;
}

.zoomedImage img {
    width: 100%;
    height: 100%;
    transition: transform 0.5s ease;
}

.loupe:hover + .zoomedImage {
    display: block;
}

.loupe:hover + .zoomedImage img {
    transform: scale(1.5);
}
.image-container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 10vh; 
  width: 105%;
  height: 200px; 
  
}

.image {
  width: 110%;
  height: 100%;
  object-fit: cover;
  border-bottom: 2px solid #6c9e41;
}


.text-overlay {
  position: absolute;
  top: 50%;
  left: 45%;
  transform: translate(-50%, -50%);
  background-color: #DE7B14; 
  padding: 03px;
  border-radius: 10px;
  text-align: center;
}

.text-box h2 {
  color: #DE7B14;
  margin: 0;
  font-family: 'Arial', sans-serif;
  font-size: 240px;
}

.text-box p {
  color: #faf6f9;
  margin: 5px 0 0 0;
  font-family: 'Arial', sans-serif;
  font-size: 16px;
}


.colored-bar {

  width: 100%;
  background-color: #FDF4D1; 
  text-align: center;
  color: #6C9E41;
  padding: 20px -0px;
  object-fit: cover; 
  margin: 0px 0 100px 0;
}

.image-container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 10vh; 
  width: 105%;
  height: 200px; 
  
}


</style>