<template>
  <div class="card">
    <img :src="srcImg" alt="" class="image">
    <h2 class="title">{{ title }}</h2>
    <p class="subtitle">{{ subtitle }}</p>
    <div class="futtor">
      <p class="price">{{ price }}</p>
      <img class="button" src='@/components/ui/ButtonCard.svg' alt="">
    </div>
  </div>
</template>

<script>
// import { ref } from 'vue'

export default {
  name: 'CardProduct',
  components: {
  },
  props: {
    title: {
      type: String,
      default: ''
    },
    price: {
      type: String,
      default: ''
    },
    subtitle: {
      type: String,
      default: ''
    },
    srcImg: {
      type: String,
      default: ''
    }
  },
  setup () {
  }
}
</script>

<style>
.card {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  text-align: center;
  width: 312px;
  height: 552px;
  border: 1px solid #D58C51
}

.image {
  position: relative;
  width: 270px;
  height: 271px;
  padding: 43px 21px 31px 21px;
}

.title {
  position: relative;
  width: 226px;
  height: 42px;
  font-family: Montserrat;
  font-weight: 500;
  font-size: 17px;
  line-height: 100%;
  letter-spacing: 0%;
  text-align: left;
  color: #FFFFFF;
  padding-left: 21px;
  padding-right: 27px;
}

.subtitle {
  position: relative;
  weight: 261px;
  height: 53px;
  font-family: Montserrat;
  font-weight: 400;
  font-size: 14px;
  line-height: 100%;
  text-align: left;
  color: #FFFFFF;
  margin-top: 13px;
  padding-left: 21px;
  padding-right: 30px;
}

.futtor {
  position: absolute;
  display:flex;
  flex-direction: row;
  align-items: center;
  margin-top: 496px;
}

.price {
  position: relative;
  font-family: Montserrat;
  font-weight: 500;
  font-size: 17px;
  line-height: 100%;
  letter-spacing: 0%;
  color: #FFFFFF;
  padding-left: 21px;
  margin-right: 159px;
}

.button {
  position: relative;
  padding-botton: 36px;
  padding-right: 32px;
}
</style>
