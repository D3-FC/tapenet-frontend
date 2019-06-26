<template>
  <button class="base-button">
    <slot/>
  </button>
</template>

<script>
export default {
  name: 'base-button'
}
</script>

<style lang="scss">
  .base-button {
    border-radius: 3px;
    border: solid 1px var(--salmon);
    background: none;
    outline: none;
    color: var(--salmon);
    padding: 14px 27px;
    min-width: 162px;
    text-transform: capitalize;
  }
</style>
