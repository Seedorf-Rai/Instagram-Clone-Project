<template>
  <template-view>
    <!-- Post Section -->
    <section class="post-section">
      <!-- Story Section -->
         <story-component/>
      <!-- Story Section Ends -->
    </section>
    <!-- Post Section Ends -->

    <!-- Suggesstion Section -->
    <!-- Suggesstion Section Ends -->
  </template-view>
</template>

<script>
import TemplateView from "./TemplateView.vue";
import StoryComponent from '@/components/StoryComponent.vue'
export default {
  components: { TemplateView,StoryComponent },
  name: "HomeView",
};
</script>

<style>

</style>