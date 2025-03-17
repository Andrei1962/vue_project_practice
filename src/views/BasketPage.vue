<template>
  <div class="container">
    <BaseActionIcon/>
    </div>
</template>

<script>
// @ is an alias to /src
import BaseActionIcon from '@/components/icons/BaseActionIcon.vue'

export default {
  name: 'BasketPage',
  components: {
    BaseActionIcon
  }
}
</script>

<style lang="css" scoped>
.container {
  widht: 1440px;
  height: 1379px;
  background-color: #161516;
}

</style>
