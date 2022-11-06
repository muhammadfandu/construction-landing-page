<template>
  <nav
    class="navbar navbar-expand-lg navbar-dark bg-dark px-4"
    style="height: 50px"
  >
    <div class="container">
      <a class="navbar-mail" href="#"
        ><font color="#ffc000"><i class="fa fa-envelope"></i></font>
        example@company.com</a
      >
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Call: +9888 5554 5445 3334</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <nav class="navbar navbar-expand-lg navbar-light bg-light px-4">
    <div class="container">
      <a class="navbar-brand" href="#"
        ><font color="#ffc000">CONS</font>TRUCT</a
      >
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">HOME</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">FEATURES</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">PROJECTS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">SERVICE</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">CONTACT US</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><i class="fa fa-search"></i></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
