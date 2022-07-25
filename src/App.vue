<template>
  <div id='app'>
    <Title msg='Sojak Studio' />
    <div id='main'>
      <Description msg='소작농 작업실!' />
      <img
        src='https://cdn.discordapp.com/attachments/983372807666815066/1000613357176504390/03645e862528cf01.png'
        height='150'
      />
      <h4>
        소작농 작업실은 디스코드 봇을 주로 개발하는 개발사 및 개발
        커뮤니티입니다.<br />
        취미로 봇을 개발하며 친구들에게 공유하여 재미를 느껴보세요!<br />
      </h4>
      <a href='https://github.com/sojakstudio' target="_blank">
        <img
          src='https://img.shields.io/badge/Sojak_Github-000000?style=for-the-badge&logo=github&logoColor=white'
          height='50'
      /></a>
      <a href='https://discord.gg/RGYnR3r5XC' target="_blank">
        <img
          src='https://img.shields.io/badge/Sojak_Discord-4374D9?style=for-the-badge&logo=discord&logoColor=white'
          height='50'
      /></a>
      <h1>다양한 봇들을 맛봐요!</h1>
      <Cdec />
      <NewKami />
      <NewGaby />
    </div>
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Description from './components/Description.vue';
import Cdec from './components/Cdec.vue';
import NewKami from './components/NewKami.vue';
import NewGaby from './components/NewGaby.vue';

export default {
  name: 'App',
  components: {
    Title,
    Description,
    Cdec,
    NewKami,
    NewGaby,
  },
};
</script>

<style>
#main {
  color: black;
  padding: 100px;
}

h1 {
  font-family: 'Helvetica';
  font-size: 80px;
  color: #f3ca5a;
}

h4 {
  font-family: 'Helvetica';
  font-size: 30px;
  color: #f3ca5a;
}

h5 {
  font-family: 'Helvetica';
  font-size: 20px;
  color: #f4ca5a;
}
</style>
