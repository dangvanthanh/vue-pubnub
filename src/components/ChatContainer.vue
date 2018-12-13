<template>
  <div class="max-w-md mx-auto">
    <div>Chat</div>
    <div class="flex flex-column">
      <div class="w-1/4 bg-teal-darker"><friend-list /></div>
      <div class="w-3/4 pl-4">
        <chat-log />
        <message-input />
      </div>
    </div>
  </div>
</template>

<script>
import FriendList from "./FriendList.vue";
import ChatLog from "./ChatLog.vue";
import MessageInput from "./MessageInput.vue";

export default {
  name: "ChatContainer",
  components: {
    FriendList,
    ChatLog,
    MessageInput
  }
};
</script>

<style></style>
