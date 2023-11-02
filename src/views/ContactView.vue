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
    <div class="info">
      <h1>My socials:</h1>
      <BoldButton class="item" text="LinkedIn" link="https://www.linkedin.com/in/jungtaek-hong/" />
      <BoldButton class="item" text="Instagram" link="https://www.instagram.com/_jung_hong/" />
      <BoldButton class="item" text="GitHub" link="https://github.com/Myshro" />
    </div>
</template>


<style scoped>
.info {
  display: flex;  
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.item {
  margin-bottom: 2rem;
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
