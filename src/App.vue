<script>
import AppHeader from '/src/AppHeader.vue'
import AppMain from '/src/AppMain.vue'
import AppFooter from '/src/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  }
}
</script>

<template>
  <!-- FontAwesome Cdn -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />

  <!-- Header Section -->
  <AppHeader />

  <!-- Main Section -->
  <AppMain />

  <!-- Footer Section -->
  <AppFooter />
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

/* Color Palette */
:root {
  --bool-bg-header: #28AFC3;
  --bool-bg-main-container: #FFFFFF;
  --bool-text-btn: #191919;
  --bool-forum-card: #FF8D61;
  --bool-text-primary: #F2F2F2;
  --bool-darker: #707070;
  --bool-first-section-title: #565656;
  --bool-first-section-text: #a3a3a3;
  --bool-white: #FFFFFF;
  --bool-black: #000000;
  --bool-orange: #FFA500;
  --bool-facebook: #3c5998;
  --bool-twitter: #54acee;
  --bool-instagram: #3f729b;
  --bool-youtube: #cd201f;
  --bool-forum-border: #28AFC3;
}
</style>