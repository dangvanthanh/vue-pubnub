<template>
  <div class=""><message-bubble v-for="n in 5" :key="n" /></div>
</template>

<script>
import MessageBubble from "./MessageBubble.vue";

export default {
  name: "ChatLog",
  components: {
    MessageBubble
  }
};
</script>

<style></style>
