<template>
  <div class="post-card">
    <h3>Titulo</h3>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eos soluta
      doloremque eaque placeat, non expedita, minima laborum reprehenderit
      voluptatum ipsum sequi dignissimos suscipit repellendus dolorem ullam
      autem earum, architecto labore!
    </p>
    <PostButton />
  </div>
</template>

<script lang="ts">
import PostButton from "./PostButton.vue";

export default {
  name: "PostCard",
  components: {
    PostButton: PostButton,
  },
};
</script>
<style scoped>
.post-card {
  border-radius: 15px;
  padding: 10px;
  margin: 5px;
  border: 1px solid #ccc;
}
</style>
