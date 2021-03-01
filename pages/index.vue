<template>

<div>
  <Navigation/>

  <Aboutus/>

  <Howitworks/>

  <Categories/>

  <Testimony/>

  <Comments/>

  <Footer/>

</div>

</template>

<script>
import Navigation from "../components/Navigation";
import Aboutus from "../components/Aboutus";
import Categories from "../components/Categories";
import Howitworks from "../components/Howitworks";
import Testimony from "../components/Testimony";
import Comments from "../components/Comments";
import Footer from "../components/Footer"
export default {
  components: {Comments, Testimony, Aboutus, Howitworks, Navigation, Categories, Footer}
}
</script>

<style>


</style>
