<template lang="html">
  <div class="chat-log">
    <chat-message
      v-for="(message, index) in messages"
      v-bind:message="message"
      v-bind:index="index"
      v-bind:key="message.id">
    </chat-message>
  </div>
</template>

<script>
export default {
  props: ['messages']
}
</script>

<style lang="css">
</style>
