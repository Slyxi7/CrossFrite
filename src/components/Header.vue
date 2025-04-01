<template>
  <div class="container-maine">
    <div class="Logo">
      <img src="../assets/logo.png" alt="Logo du site" />
    </div>
    <div class="ElementNav">
      <p>Accueil</p>
      <p>Abonnement</p>
      <p>Contact</p>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.container-maine {
  display: flex;
  position: relative;
  background-color: white;
  align-items: center;
  justify-content: space-between;
  border-bottom: 2px solid black;
  width: 100vw;
  height: auto;
}
.Logo {
  width: 105px;
  height: 105px;
}
.Logo img {
  width: 105px;
  height: auto;
}

.ElementNav {
  display: flex;
  justify-content: center;
  width: 100%;
  justify-content: space-around;
}

.ElementNav p {
  font-size: 32px;
  cursor: pointer;
  font-family: 'Inter', sans-serif;
  font-weight: 600;
}
</style>
