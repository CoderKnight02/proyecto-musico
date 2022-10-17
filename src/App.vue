<script>
import Header from './components/Header.vue';
import AboutMe from './components/AboutMe.vue';
import Newest from './components/Newest.vue';
import Contactame from './components/Contactame.vue';

    export default{
    data() {
    },
    components: {
    Header,
    AboutMe,
    Newest,
    Contactame
}
}

</script>

<template>

  <Header></Header>
  <AboutMe></AboutMe>
  <Newest></Newest>
  <Contactame></Contactame>


</template>
