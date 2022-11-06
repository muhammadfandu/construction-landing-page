<template>
  <div id="app">
    <Home></Home>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Home from './components/Home.vue';

export default {
  name: 'App',
  components: {
    Home,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.carousel-indicators button {
  background-color: #ffc000 !important;
}

.navbar {
  height: 80px;
}

.navbar-brand {
  font-weight: 800;
}

.navbar-mail {
  text-decoration: none;
  font-weight: 400;
  color: #f8f9fa;
}

.navbar .nav-item {
  margin: 0 20px;
  font-weight: 700;
}

.navbar .nav-item.active .nav-link {
  color: #ffc000;
}

.container.width-80 {
  max-width: 80% !important;
}

.mr-auto {
  margin-right: auto;
}
.ml-auto {
  margin-left: auto;
}

.float-left {
  float: left;
}

.float-right {
  float: right;
}

.text-left {
  text-align: left;
}

.text-right {
  text-align: right;
}

.font-weight-bold {
  font-weight: 500;
}

.btn-round {
  width: 80px;
  height: 80px;
  border-radius: 40px;
  margin: 30px auto;
  font-size: 2rem;
}

.btn-primary {
  background-color: #ffc000;
  border: 1px solid #ffc000;
}

.btn-primary:hover {
  background-color: #eeb000;
  border: 1px solid #ffc000;
}

.btn-secondary {
  background-color: #2e3e50;
  border: 1px solid #2e3e50;
}

.btn-default {
  background-color: white;
  color: #ffc000;
}
</style>
