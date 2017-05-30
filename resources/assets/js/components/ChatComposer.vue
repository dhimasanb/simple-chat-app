<template lang="html">
  <div class="chat-composer">
    <input type="text" name="" value="" placeholder="Start typing your message...">
    <button type="button" class="btn btn-primary" name="button">Send</button>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
.chat-composer {
  display: flex;
}

.chat-composer input {
  flex: 1 auto;
}

.chat-composer button {
  border-radius: 0;
}
</style>
