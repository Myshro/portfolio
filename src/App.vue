<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import MyHeader from './components/MyHeader.vue'
</script>

<template>
  <header>
    <div class="container">
      <img class="me" src="/running.png" alt="A running pixelated man">
      <RouterLink class="navigation-item" to="/">Home</RouterLink>
      <RouterLink class="navigation-item" to="/about">About</RouterLink>
      <RouterLink class="navigation-item" to="/projects">Projects</RouterLink>
      <RouterLink class="navigation-item" to="/contact">Contact</RouterLink>
    </div>
  </header>
  <RouterView/>
</template>

<style scoped>
  * {
    font-size: 1.5rem;
  }
  @media (max-width: 800px) {
    .container {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      align-items: center;
      gap: 3rem;
    } 
    .navigation-item {
      font-size: 3rem;
    }
  }
  .navigation-item {
    text-decoration: none;
    border-radius: 5px;
    padding: 3px;
  }
  .navigation-item:hover {
    cursor: pointer;
    background-color: var(--black);
    color: white;
  }
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 5% 0 5%;
  }
  
  .me {
    width: 4rem;
    height: 4rem;
    border: 8px solid;
    border-radius: 15px;
    border-style: double;
  }

  #me:hover {
    opacity: 0;
  }

  header {
    font-weight: 600;
    font-size: 1.5rem;
    z-index: 50;
    top: 0;
    box-sizing: border-box;
    width: 100%;
    padding: 3rem;
    transition: all .2s ease-in-out;
    /* border-bottom: 4px solid black; */
    padding-bottom: 6rem;
  }
</style>