<template>
  <div id="description">
    <h3>{{ sub }}</h3>
    <h4>{{ msg }}</h4>
  </div>
</template>

<script>
export default {
  name: 'Desciption',
  props: {
    sub: String,
    msg: String
  }
}
</script>

<style>
#description {
  font-family: 'Helvetica';
  color: #FFFFA2;
  padding-top: 30px;
  padding: 100px;
}

h3 {
  font-size: 40px;
}

h4 {
  font-size: 25px;
  color: #F2CB61;
}
</style>
