<template>
  <div id="projects">
    <div class="container my-4 px-4">
      <div class="text-center">
        <span class="welcome-span">We offer</span>
        <h1 class="welcome-header">
          <font color="#ffc000">View </font>Our Projects Gallery
        </h1>
        <p class="welcome-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation
        </p>
      </div>

      <div class="row">
        <nav class="navbar navbar-expand-lg navbar-light">
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav nav-projects">
              <a class="nav-item nav-link active">ALL WORKS</a>
              <a class="nav-item nav-link">CONSTRUCTION</a>
              <a class="nav-item nav-link">ARCHITECTURES</a>
              <a class="nav-item nav-link">INTERIOR</a>
            </div>
          </div>
        </nav>
      </div>
    </div>

    <div class="container-fluid">
      <div class="row mt-4">
        <div class="col-img-3">
          <img
            src="https://picsum.photos/id/232/300/300"
            class="d-block w-100"
            alt="https://picsum.photos/300/300"
          />
          <div class="overlay">
            <a class="icon" title="User Profile">
              <i class="fa fa-eye"></i>
            </a>
          </div>
        </div>
        <div class="col-img-3">
          <img
            src="https://picsum.photos/id/238/300/300"
            class="d-block w-100"
            alt="https://picsum.photos/300/300"
          />
          <div class="overlay">
            <a class="icon" title="User Profile">
              <i class="fa fa-eye"></i>
            </a>
          </div>
        </div>
        <div class="col-img-3">
          <img
            src="https://picsum.photos/id/153/300/300"
            class="d-block w-100"
            alt="https://picsum.photos/300/300"
          />
          <div class="overlay">
            <a class="icon" title="User Profile">
              <i class="fa fa-eye"></i>
            </a>
          </div>
        </div>
        <div class="col-img-3">
          <img
            src="https://picsum.photos/id/641/300/300"
            class="d-block w-100"
            alt="https://picsum.photos/300/300"
          />
          <div class="overlay">
            <a class="icon" title="User Profile">
              <i class="fa fa-eye"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Projects',
  components: {},
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#projects {
  margin: 100px 0;
}

.nav-projects {
  margin: 0 auto;
}

.nav-projects .nav-item {
  color: #333;
  font-weight: 600;
}

.nav-projects .nav-item.active {
  color: #ffc000;
  font-weight: 600;
}

.col-img-3 {
  position: relative;
  max-width: 25%;
  padding: 0;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: 0.3s ease;
  background-color: #ffc00099;
  z-index: 100;
}

/* When you mouse over the container, fade in the overlay icon*/
.col-img-3:hover .overlay {
  opacity: 1;
}

/* The icon inside the overlay is positioned in the middle vertically and horizontally */
.icon {
  color: white;
  font-size: 2rem;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.icon:hover {
  color: #eee;
}
</style>
