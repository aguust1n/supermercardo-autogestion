<template>
  <v-app>
    <navbar/>
    <v-main class="mt-4 mb-8 mx-4 mx-sm-10 mx-lg-16">
      <router-view/>
    </v-main>
    <Footer/>
  </v-app>
</template>

<script>

import Footer from "./layout/Footer";
import Navbar from "./layout/Navbar";
export default {
  name: 'App',
  components: {Navbar, Footer},
  data: () => ({
    //
  }),
};
</script>

<style>
@font-face {
font-family: Montserrat-Bold;
src: url('/fonts/Montserrat-Bold.ttf');
}
@font-face {
  font-family: Montserrat-Regular;
  src: url('/fonts/Montserrat-Regular.ttf');
}
@font-face {
  font-family: Montserrat-SemiBold;
  src: url('/fonts/Montserrat-SemiBold.ttf');
}
@font-face {
  font-family: Montserrat-SemiBoldItalic;
  src: url('/fonts/Montserrat-SemiBoldItalic.ttf');
}

.Montserrat {
font-family: "Montserrat";
}
.Montserrat-Bold {
  font-family: "Montserrat-Bold";
}

</style>
