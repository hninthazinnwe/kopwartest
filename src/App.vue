<template>
  <div class="container">
    <navbar />
    <home/>
    <about/>
    <footer1/>
  </div>
</template>
<script>
import home from './components/home.vue';
import navbar from './components/header.vue';
import about from './components/about.vue';
import footer1 from './components/footer.vue';

export default {
  components: {
    home,
    navbar,
    about,
    footer1
  }
}

</script>
<style>
.container {
  padding: 0px;
  width: 100%;
  max-width: initial;
}


</style>