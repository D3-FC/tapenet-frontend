<template>
  <section class="base-card">
    <slot />
  </section>
</template>

<script>
export default {
  name: 'base-card'
}
</script>

<style lang="scss">
  .base-card {
    border-radius: 10px;
    box-shadow: 0 -1px 54px 0 rgba(208, 211, 218, 0.5);
    background-color: #ffffff;
  }
</style>
