<template>
  <div>
    <!-- NavBar Section  -->
  <nav-bar/>
  <!-- NavBar Section Ends -->
  <!-- Story Section -->
   <slot></slot>
  <!-- Story Section Ends -->
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
export default {
  name: 'TemplateView',
  components: { NavBar}
}
</script>

<style>

</style>