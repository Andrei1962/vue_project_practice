<template>
  <div class="container">
    <HeaderMain/>
    <CardsMain/>
    </div>
</template>

<script>
// @ is an alias to /src
import HeaderMain from '@/components/blocks/HeaderMain.vue'
import CardsMain from '@/components/blocks/CardsMain.vue'

export default {
  name: 'MainPage',
  components: {
    HeaderMain,
    CardsMain
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
