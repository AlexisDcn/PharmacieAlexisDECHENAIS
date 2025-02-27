<script setup>
import MedicamentList from "./components/MedicamentList.vue";
</script>

<template>
  <div id="app" class="app-style">
    <header class="header">
      <img src="@/assets/logo.png" alt="Logo" class="logo" />
      <div class="title-group">
        <h1 class="title">La Pharmacie d'Alexis</h1>
        <p class="subtitle">Votre pharmacie préférée : où les pilules sont amères, mais l'ambiance est douce !</p>
      </div>
    </header>
    <MedicamentList />
  </div>
</template>

<style>
.app-style {
  font-family: Arial, sans-serif;
  text-align: center;
  background-color: #f8f9fa;
  min-height: 100vh;
  padding: 20px;
}
.header {
  background-color: #007bff;
  color: white;
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
.logo {
  height: 100px;
  margin-right: 20px;
}
.title-group {
  flex: 1;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.title {
  margin: 0;
  font-size: 2.5em;
  font-weight: bold;
}
.subtitle {
  margin: 10px 0;
  font-size: 1.2em;
  color: #ddd;
}
</style>
