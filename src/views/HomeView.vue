<template>
  <template-view>
     <!-- Post Section -->
      <section class="post-section">

      </section>
     <!-- Post Section Ends -->

     <!-- Suggesstion Section -->
     <!-- Suggesstion Section Ends -->
  </template-view>
</template>

<script>
import TemplateView from './TemplateView.vue'
export default {
  components: { TemplateView },
  name: 'HomeView',
}
</script>

<style>
.post-section{
  width: 500px;
  height: 100vh;
  background-color: red;
  margin-left: 23%;
}
</style>