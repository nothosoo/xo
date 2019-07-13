<template>
  <div class="index-container">
    <div class="link-wrapper">
      <nuxt-link class="button link" to="about">ABOUT</nuxt-link>
      <nuxt-link class="button link" to="contact">CONTACT</nuxt-link>
    </div>
    <div class="text-wrapper">
      <h2 class="greetings">Hey</h2>
      <h1 class="name">I'm Khosoo</h1>
    </div>
    <div class="personal-links">
      <a target="_blank" href="https://instagram.com/hosukechi" class="link">Instagram</a>
      <a target="_blank" href="#" class="link">Github</a>
      <a target="_blank" href="https://gitlab.com/nothosoo" class="link">Gitlab</a>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    
  }
}
</script>

<style lang="scss">

</style>
