<template>
  <div>
    <Header></Header>
    <BoxDownload></BoxDownload>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import BoxDownload from "./components/BoxDownload";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: { Header, BoxDownload, Footer }
};
</script>

<style></style>
