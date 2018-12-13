<template>
  <div><friend-list-item v-for="n in 5" :key="n" /></div>
</template>

<script>
import FriendListItem from "./FriendListItem.vue";

export default {
  name: "FriendList",
  components: {
    FriendListItem
  }
};
</script>

<style></style>
