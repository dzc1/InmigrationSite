<template>
  <div>
    <NavBar />
    <Hero v-for="hero in 1" :key="hero" />
    <Why />
    <Solutions />
    <Footer />
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
</style>