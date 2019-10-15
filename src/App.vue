<template>
  <div id="app" class="container-fluid">
    <div class="text-center bg-warning p-1">
        <a href="#">
          <i class="m-2 fab fa-twitter fa-lg text-danger" ></i>
        </a>
        <a href="#">
          <i class="m-2 fab fa-facebook fa-lg text-danger" ></i>
        </a>
        <a href="#">
          <i class="m-2 fab fa-instagram fa-lg text-danger" ></i>
        </a>
        <a href="#">
          <i class="m-2 fab fa-youtube fa-lg text-danger" ></i>
        </a>
    </div>
    <Store/>
    <!--Menu/>
    <Slider/>
    <MainBody/>
    <MenWomen/>
    <JoinUs/>
    <BmEvents/>
    <ContactBM/>
    <Footer/-->
    <!--img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/-->

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Menu from "@/components/Menu";
import Slider from "@/components/Slider";
import 'bootstrap/dist/css/bootstrap.min.css';
import 'jquery'
import MainBody from "@/components/MainBody";
import JoinUs from "@/components/JoinUs";
import 'bootstrap-css-only/css/bootstrap.min.css';
import 'mdbvue/build/css/mdb.css';
import MenWomen from "@/components/MenWomen";
import { mdbIcon } from 'mdbvue';
import BmEvents from "@/components/BmEvents";
import ContactBM from "@/components/ContactBM";
import Footer from "@/components/Footer";
import Store from "@/components/Store";

export default {
  name: 'app',
  components: {
    mdbIcon,
    HelloWorld,
    Menu,
    Slider,
    MainBody,
    JoinUs,
    MenWomen,
    ContactBM,
    Footer,
      Store
  }
}
</script>

<style>
  @import "~bootstrap/dist/css/bootstrap.min.css";
#app {
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;*/
  background-color: black;
}
</style>
