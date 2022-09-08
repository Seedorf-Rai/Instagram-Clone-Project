<template>
  <div class="small-div">
        <div class="story-div-bg">
          <div class="story-img-bg">
            <img
              :src="storyLink"
              class="story-profile"
              alt=""
            />
          </div>
        </div>
        <p class="story-name">{{ storyName }}</p>
    </div>
</template>

<script>
export default {
  name: 'StoryView',
  props: ['storyLink','storyName']
}
</script>

<style>

</style>