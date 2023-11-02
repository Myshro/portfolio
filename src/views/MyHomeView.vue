<script setup>
  // import WelcomeItem from "../components/WelcomeItem.vue"
  import DocumentationIcon from '../components/icons/IconDocumentation.vue'
  import ToolingIcon from '../components/icons/IconTooling.vue'
  import EcosystemIcon from '../components/icons/IconEcosystem.vue'
  import CommunityIcon from '../components/icons/IconCommunity.vue'
  import SupportIcon from '../components/icons/IconSupport.vue'
  import BoldButton from '../components/BoldButton.vue'

</script>

<template>
  <div class="about">
    <div class="info">
      <h1>Hey there!</h1>
      <h2>My name is Jungtaek, nice to meet you.</h2>
      <p>I'm currently a first-year computer science student at the <b id="name">University of Virginia.</b> 
        I am interested in editing, designing websites, and learning more about programming!
      </p>
    </div>
    <div class="container">
      <img id="me" src="../../public/running.gif" alt="A picture of me!">
    </div>
  </div>
</template>

<style scoped>
#name {
  background: linear-gradient(to right, #ff5500, #ff1100);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.about {
  display: flex;
  justify-content: space-evenly;
  align-items: center;

}
#resume  {
  background-color: white;
  border: 3px solid var(--black);
  border-radius: 5px;
  box-shadow: -3px 5px var(--black);
  padding: 2rem 5rem;
  font-size: 1.25rem;
  text-align: center;
  font-weight: 600;
  font-size: 1.4444rem;
  align-self: flex-start;
}
#resume:hover {
  background-color: var(--black);
  color: white;
  cursor: pointer;
}
.info {
  max-width: 40%;
  display: flex;
  flex-direction: column;
  justify-content: right;
  align-items: left;

}
#me {
  border-radius: 100%;
  border: 0.5rem solid;
  max-width: 400px;
  max-height: 400px;
  margin: 0;
}

@media (max-width: 800px) {
  #me {
    visibility: hidden;
  }
}

h1 {
  font-size: 4rem;
}
h2 {
  font-size: 2rem;
  margin-bottom: 3rem;
}
.container h2 {
  text-align: center;
  font-size: 1.5rem;
}
p {
  font-size: 1.4444rem;
  font-family: 'IBM Plex Sans';
  max-width: 1000px;
  margin-bottom: 3rem;
  line-height: 1.5;
}
</style>
