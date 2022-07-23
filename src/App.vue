<template>
  <div id="app">
    <Title msg="Sojak Studio" />
    <Description sub="소작농 작업실!"
      msg=
      "
      소작농 작업실은 구알릭, 마실롯이 설립한 프로그래밍 회사입니다.
      "
    />
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Description from './components/Description.vue';

export default {
  name: 'App',
  components: {
    Title,
    Description
  }
}
</script>
