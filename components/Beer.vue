<template>
    <div class="container">
      <p class="text-overlay">hello beer</p>
      <input type="text" placeholder="Username" class="input-field" />
      <input type="password" placeholder="Password" class="input-field" />
      <button class="submit-button">Login</button>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  /* Assurez-vous que le body et html occupent tout l'écran */
  body, html {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
  }
  
  /* Conteneur principal */
  .container {
      width: 100vw;
      height: 100vh;
      background: url('/assets/backgroundDesktop.svg') no-repeat center center;
      background-size: cover; /* Adapte l'image au conteneur tout en la couvrant */
      display: flex;
      justify-content: center; /* Centre horizontalement */
      align-items: center; /* Centre verticalement */
      flex-direction: column;
      gap: 20px; /* Espacement entre les éléments */
  }
  
  /* Texte overlay */
  .text-overlay {
      color: black; /* Couleur du texte */
      font-size: 6rem; /* Taille du texte */
      font-weight: bold;
      text-align: center;
      font-family: Phonk;
  }
  
  /* Champs de saisie */
  .input-field {
      width: 80%; /* Largeur des champs */
      max-width: 400px; /* Limite la largeur */
      padding: 15px;
      font-size: 1rem;
      border-radius: 10px;
      outline: none;
      transition: all 0.3s ease-in-out;
  }
  
  
  /* Bouton de connexion */
  .submit-button {
      width: 80%;
      max-width: 400px;
      padding: 15px;
      font-size: 1rem;
      background-color: #a296ff;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s ease-in-out;
  }
  </style>