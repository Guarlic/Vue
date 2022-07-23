<template>
  <div id="HelloWorld">
    <img src="../../../Desktop/소작로고.png" height="600"/>
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
  text-align: center;
  font-size: 100px;
}
</style>
