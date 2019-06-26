<template>
  <div class="base-avatar">
    <img
      src="https://picsum.photos/200"
      alt="avatar"
    >
  </div>
</template>

<script>
export default {
  name: 'base-avatar'
}
</script>

<style lang="scss">
  .base-avatar {
    width: 139px;
    height: 139px;
    border-radius: 139px;
    overflow: hidden;
    img {
      max-width: 100%;
      max-height: 100%;
      vert-align: middle;
    }
  }
</style>
