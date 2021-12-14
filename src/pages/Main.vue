<template>
  <div class="main">
    <Header />

    <div class="hero">
      <div class="hero__bloc">
      </div>
    </div>

    <div class="preview">
      <div class="preview__bloc"></div>
      <div class="preview__bloc"></div>
      <div class="preview__bloc"></div>
    </div>

    <div class="img">
      <div class="img__bloc"></div>
    </div>

    <Footer />

  </div>
</template>

<script>
import "../assets/sass/main.scss";
import Header from "../components/Header";
import Footer from "../components/Footer";

export default {
  name: 'Main',
  components: {
    Header,
    Footer,
  }
}
</script>
