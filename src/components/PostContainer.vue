<template>
  <div class="post-container">
    <PostCard />
  </div>
</template>
<script lang="ts">
import PostCard from "./PostCard.vue";

export default {
  name: "PostContainer",
  components: {
    PostCard: PostCard,
  },
};
</script>
<style>
.post-container {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
}
</style>
