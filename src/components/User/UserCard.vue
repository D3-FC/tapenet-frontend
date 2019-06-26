<template>
  <base-card class="user-card">
    <base-avatar class="user-card__avatar"/>
    <p class="user-card__name">Shkodran Arifi</p>
    <base-button class="user-card__button">
      my profile
    </base-button>

  </base-card>
</template>

<script>
import BaseCard from '../Card/BaseCard'
import BaseAvatar from '../Avatar/BaseAvatar'
import BaseButton from '../Button/BaseButton'
export default {
  name: 'user-card',
  components: { BaseButton, BaseAvatar, BaseCard }
}
</script>

<style lang="scss">
  .user-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 397px;
    padding: 33px;
    box-sizing: border-box;

    &__name{
      font-family: Roboto;
      font-size: 24px;
      letter-spacing: 1.5px;
      color: #9b9b9b;
    }

    &__button{
      margin-top: auto;
    }

    &__avatar{
      margin-top: 28px;
    }
  }
</style>
