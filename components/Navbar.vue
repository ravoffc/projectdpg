<template>
  <main>
    <ul class="nav justify-content-center">
      <li class="nav-item">
        <NuxtLink class="nav-link text-dark" to="/">Home</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink class="nav-link text-dark" to="/about">About</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink class="nav-link text-dark" to="/gallery">Gallery</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink class="nav-link text-dark" to="/contact">Contact</NuxtLink>
      </li>
    </ul>
  </main>
</template>

<script>
export default {

}
</script>

<style scoped>
Nuxtlink {
  color: rgb(0, 110, 255);
}
</style>
