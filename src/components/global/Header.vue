<template>
  <header>
    <div class="container">
      <Navbar />
    </div>
  </header>
</template>

<script>
import Navbar from './Navbar';

export default {
  name: 'Header',
  components: {
    Navbar
  }
}
</script>

<style>
  header {
    background-color: #2196f3;
    padding-top: 5px;
    padding-bottom: 5px;
    position: relative;
    margin-bottom: 5rem;
  }
</style>