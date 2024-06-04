<script setup>

</script>

<template>
  <nav>
    <router-link :to="{ name: 'home' }">Home</router-link>
    <router-link :to="{ name: 'about' }">About</router-link>
    <router-link :to="{ name: 'profile' }">profile</router-link>
    <router-link :to="{ name: 'contact' }">Contact</router-link>
  </nav>
  <router-view />
</template>

<style scoped>
 nav{
    text-align: center;
  }
</style>