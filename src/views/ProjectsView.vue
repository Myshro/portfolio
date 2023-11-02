<script setup>
  // import WelcomeItem from "../components/WelcomeItem.vue"
  import DocumentationIcon from '../components/icons/IconDocumentation.vue'
  import ToolingIcon from '../components/icons/IconTooling.vue'
  import EcosystemIcon from '../components/icons/IconEcosystem.vue'
  import CommunityIcon from '../components/icons/IconCommunity.vue'
  import SupportIcon from '../components/icons/IconSupport.vue'

</script>

<template>
  <div class="about">
    <div class="info">
      <h1>Projects:</h1>
      <h2>Under construction...</h2>
    </div>
  </div>
</template>


<style scoped>
.about {
  display: flex;  
  justify-content: center;
  align-items: center;
  gap: 20px;
  align-items: top;

}
#resume  {
  background-color: white;
  margin-top: 3rem;
  border: 3px solid var(--black);
  border-radius: 5px;
  box-shadow: -3px 5px var(--black);
  padding: 2rem 5rem;
  font-size: 1.25rem;
  text-align: center;
  margin: auto;
  font-weight: 600;
  font-size: 1.4444rem;
}
#resume:hover {
  background-color: var(--black);
  color: white;
  cursor: pointer;
}
.info {
  max-width: 40%;
}
#me {
  border-radius: 100%;
  border: 0.5rem solid;
  max-width: 500px;
  max-height: 500px;
  margin: 0;

}
h1 {
  font-size: 4rem;
  margin-bottom: 3rem;
}
.container h2 {
  text-align: center;
  font-size: 1.5rem;
}
p {
  font-size: 1.44rem;
  font-family: 'IBM Plex Sans';
  padding-bottom: 3rem;
  line-height: 1.5;
}
.colored-bold {
  background: linear-gradient(to right, #00adf1, #002aff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 700;
}
</style>
