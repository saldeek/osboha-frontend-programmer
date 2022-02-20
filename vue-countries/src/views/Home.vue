<template>
  <Header></Header>
  <About></About>
  <CountriesList></CountriesList>
  <Footer></Footer>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";
import About from "@/components/About";
import CountriesList from "@/components/CountriesList";

export default {
  name: "Home",
  components: {
    About,
    CountriesList,
    Header,
    Footer,
  },
};
</script>
