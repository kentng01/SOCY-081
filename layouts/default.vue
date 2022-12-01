<template>
    <div id="__app">
        <NavOverlay/>
        <Nuxt />
    </div>
</template>

<script>

export default {
  name: 'NuxtLayout',
  
}

</script>

<style scoped>

@keyframes fade {
  0% {
    opacity: 0
  }  
  100% {
    opacity: 1
  }
}

#__app {
  animation: fade 5s linear forwards;
  padding: 3.5rem;
  background-image: 
    linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), 
    url('@/assets/images/fleeting-colors.jpg');
  background-size: cover;
}

@media screen and (max-width: 767px) {
  
  #__app {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }

}

</style>
