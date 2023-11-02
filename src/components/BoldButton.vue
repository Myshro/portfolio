<script setup>
  defineProps(['text', 'link', 'style']);
</script>

<template>
    <a :style="style" :href="link" target="_blank"> {{ text }} </a>
</template>

<style scoped>

a {
  background-color: white;
  border: 3px solid var(--black);
  border-radius: 5px;
  box-shadow: -3px 5px var(--black);
  padding: 2rem 4rem;
  font-size: 1.25rem;
  text-align: center;
  font-weight: 600;
  font-size: 1.4444rem;
  /* align-self: flex-start; */
}
a:hover {
  background-color: var(--black);
  color: white;
  cursor: pointer;
}

</style>

