<template>
  <div class="container">
    <stream/>
  </div>
</template>

<script>
import stream from '../components/Stream/Stream.vue'
export default {
  components: {
    stream
  }
}
</script>

<style lang="scss" scoped>
.container {
  height: 100vh;
  background-image: url(../assets/live-stream.png);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

