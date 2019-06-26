<template>
  <div>
    <base-button>
      My Profile
    </base-button>
    <base-avatar/>

    <user-card/>
  </div>
</template>

<style lang="scss">
:root{
  --salmon: #ff8376
}

body{
  background: #f7f8fa;
}
</style>

<script>
import BaseButton from './components/Button/BaseButton'
import BaseAvatar from './components/Avatar/BaseAvatar'
import BaseCard from './components/Card/BaseCard'
import UserCard from './components/User/UserCard'
export default {
  components: { UserCard, BaseCard, BaseAvatar, BaseButton }
}
</script>
