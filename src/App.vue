<template>
  <Navbar />
  <TopBanner />
  <Main />
  <Footer />
</template>

<script>
import Navbar from "./components/layouts/Navbar";
import Footer from "./components/layouts/Footer";
import TopBanner from "./components/TopBanner";
import Main from "./components/Main";

export default {
  name: "App",
  components: {
    Navbar,
    TopBanner,
    Main,
    Footer
  }
};
</script>
