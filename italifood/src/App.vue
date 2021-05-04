<template>
  <div id="app">
    <HeaderFood/>
    <SectionMenu/>
    <SectionMoreInfo/>
    <SectionMenuDish/>
    <SecArtPizz/>
    <SecArtCard/>
  </div>
</template>

<script>
import HeaderFood from './components/HeaderFood.vue'
import SectionMenu from './components/SectionMenu.vue'
import SectionMoreInfo from './components/SectionMoreInfo.vue'
import SectionMenuDish from './components/SectionMenuDish.vue'
import SecArtPizz from './components/SecArtPizz.vue'
import SecArtCard from './components/SecArtCard.vue'

export default {
  name: 'App',
  components: {
   HeaderFood,
   SectionMenu,
   SectionMoreInfo,
   SectionMenuDish,
   SecArtPizz,
   SecArtCard

  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400&display=swap');

  @font-face {
    font-family: 'Reey';
    src: url('../src/assets/fonts/Reey-Regular.woff2') format('woff2'),
        url('/src/assets/fonts/Reey-Regular.woff') format('woff');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}
a{
  text-decoration: none;
}

  html, body{
    margin: 0;
    padding: 0;
    outline: 0;
    font-family: 'Open Sans', sans-serif;
  }

  .flex{
    display: flex;
  }
  .flex1{
    flex: 1;
  }
    .flex2{
    flex: 2;
  }
    .flex3{
    flex: 3;
  }
  .flex-directino-column{
    flex-direction: column;
  }

</style>
