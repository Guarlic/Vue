<template>
  <div id="HelloWorld">
    <img src="../../../Desktop/소작로고.png" height="150"/>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
#HelloWorld {
  font-family: 'Helvetica';
  text-align: center;
  font-size: 40px;
  color: #F6DB90;
  padding: 60px;
}
</style>
