<template>
  <the-hader title="RememberMe"> </the-hader>
  <the-resources></the-resources>
</template>
<script>
import TheHader from './components/layouts/TheHader.vue';
import TheResources from './components/learning-resources/TheResources.vue';

export default {
  components: {
    TheHader,
    TheResources,
  },
  data() {
    return {};
  },
};
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>
