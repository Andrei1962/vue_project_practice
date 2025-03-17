<template>
  <div class="container">
    <HeaderMain/>
    <BaseActionIcon add/>
    <CardsMain/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderMain from '@/components/blocks/HeaderMain'
import CardsMain from '@/components/blocks/CardsMain'
import BaseActionIcon from '@/components/icons/BaseActionIcon'

export default {
  name: 'MainPage',
  components: {
    HeaderMain,
    CardsMain,
    BaseActionIcon
  }
}
</script>

<style lang="css" scoped>
.container {
  widht: 1440px;
  height: 100vh;
  background-color: #161516;
}

</style>
