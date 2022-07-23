<template>
  <div id="app">
    <Title msg="Sojak Studio" />
    <Description msg="소작농 작업실!" />
    <h4>
      소작농 작업실은 디스코드 봇을 주로 개발하는 개발사입니다.<br />
      취미로 봇을 개발하며 친구들에게 공유하여 재미를 느껴보세요!<br />
      꺠미, 가비, 시덱이 다양한 봇들을 맛봐요!
    </h4>
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Description from "./components/Description.vue";

export default {
  name: "App",
  components: {
    Title,
    Description,
  },
};
</script>

<style>
h4 {
  font-family: "Helvetica";
  font-size: 30px;
  color: #f3ca5a;
  padding: 100px;
}
</style>
