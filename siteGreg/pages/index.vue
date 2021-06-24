<template>
  <div class="w-screen h-auto bg-gray-800 flex flex-row">
    <the-navbar />
    <the-lmargin />
    <the-context />
  </div>
</template>

<script>
import TheContext from '../components/TheContext.vue'
import TheLmargin from '../components/TheLmargin.vue'
import TheNavbar from '../components/TheNavbar.vue'
export default {
  components: { TheNavbar, TheContext, TheLmargin },}
</script>
