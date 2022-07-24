<template>
  <div id="app">
    <Title msg="Sojak Studio" />
    <div id="main">
      <Description msg="소작농 작업실!" />
      <h4>
        소작농 작업실은 디스코드 봇을 주로 개발하는 개발사입니다.<br />
        취미로 봇을 개발하며 친구들에게 공유하여 재미를 느껴보세요!<br />
        꺠미, 가비, 시덱이 다양한 봇들을 맛봐요!<br />
      </h4>
      <a href="https://github.com/sojakstudio" target="_blank">
        <img
          src="https://img.shields.io/badge/Sojak_Github-000000?style=for-the-badge&logo=github&logoColor=white"
          height="50"
      /></a>
    </div>
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
#main {
  color: black;
}

h4 {
  font-family: "Helvetica";
  font-size: 30px;
  color: #f3ca5a;
  padding: 100px;
}

a {
  padding: 100px;
}
</style>
