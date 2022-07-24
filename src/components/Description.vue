<template>
  <div id="description">
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
export default {
  name: "Desciption",
  props: {
    msg: String,
  },
};
</script>

<style>
#description {
  font-family: "Helvetica";
  font-size: 40px;
  color: #ffffa2;
}
</style>
