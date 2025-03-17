<template>
  <header class="header">
    <div class="container">
      <a class="headertitle" href="">наша продукция</a>
      <a class="headerdescription" href="">3 товара<br>на сумму 3 500 ₽</a>
      <img class="logo" src="@/components/icons/BasketIcon.svg" alt="">
    </div>
  </header>
</template>

<script>

export default {
  name: 'HeaderMain',
  props: {
    name: {
      type: String,
      default: ''
    }
  },
  setup () {
  }
}
</script>

<style lang="css" scoped>
.header {
  background-color: #161516;
  padding: 13px;
  top: 48px;
  margin-botton:25px;
}

.container {
  position: relative;
  max-width: 1440px;
  height: 52px;
  display: flex;
  align-items: center;
  margin: 0 auto;
}

.headertitle {
  position: relative;
  display: inline-block;
  width: 535px;
  height: 38px;
  font-family: Montserrat;
  font-weight: 700;
  font-size: 31px;
  line-height: 100%;
  letter-spacing: 0%;
  text-transform: uppercase;
  color: #ffffff;
  text-decoration: none;
  padding-left: 40px;
}

.headerdescription {
  position: relative;
  display: inline-block;
  width: 171px;
  height: 42px;
  font-family: Montserrat;
  font-weight: 500;
  font-size: 17px;
  line-height: 100%;
  letter-spacing: 0%;
  text-align: right;
  text-decoration: none;
  color: #ffffff;
  margin-left: 524px;
  padding: 15px 0 15px 0;
}

.logo {
  position: relative;
  color: #ffffff;
  padding-right: 70px;
  padding-left: 20px;
}

</style>
