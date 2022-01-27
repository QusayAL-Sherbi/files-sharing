<template>
  <Header />
  <div class="mb-4">
    <div class="container d-flex justify-content-between">
      <h3 class="align-left">Share Files</h3>
      <p>Class</p>
    </div>
  </div>
  <div class="container">
    <div class="row">
      <div class="col-lg-4">
        <Sidebar />
      </div>
      <div class="col-lg-8">
        <Main-Section />
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/global/Header';
import Sidebar from './components/Sidebar';
import MainSection from './components/Main-Section';

export default {
  name: 'App',
  components: {
    Header,
    Sidebar,
    MainSection
  }
}
</script>

<style>
/* body {
  background-color: #EEE;
} */

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #f5f6fa;
  color: #2c3e50;
}
</style>
