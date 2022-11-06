<template>
  <div id="welcome">
    <div class="container width-80 my-4 px-4">
      <div class="text-center">
        <span class="welcome-span">We offer</span>
        <h1 class="welcome-header">
          <font color="#ffc000">Welcome </font>to Free PSD Construction Template
        </h1>
        <p class="welcome-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation
        </p>
      </div>

      <div class="row my-4">
        <div class="col-3">
          <div class="card active">
            <button class="btn btn-primary btn-round">
              <i class="fa fa-paint-brush"></i>
            </button>
            <h4 class="card-header">CREATIVE IDEAS</h4>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            </p>
          </div>
        </div>

        <div class="col-3">
          <div class="card">
            <button class="btn btn-default btn-round">
              <i class="fa fa-file-text-o"></i>
            </button>
            <h4 class="card-header">PLANNING</h4>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            </p>
          </div>
        </div>

        <div class="col-3">
          <div class="card">
            <button class="btn btn-default btn-round">
              <i class="fa fa-info"></i>
            </button>
            <h4 class="card-header">SAFE WORK</h4>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            </p>
          </div>
        </div>

        <div class="col-3">
          <div class="card">
            <button class="btn btn-default btn-round">
              <i class="fa fa-cog"></i>
            </button>
            <h4 class="card-header">BEST QUALITY</h4>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Welcome',
  components: {},
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#welcome {
  margin: 100px 0;
}

.welcome-header {
  font-size: 2.2rem;
  font-weight: 800;
}

.welcome-text {
  font-size: 1.2rem;
  margin: 20px 200px;
}

.welcome-span {
  margin: 20px 0;
  font-size: 1rem;
  font-weight: 500;
}

#welcome .card {
  background-color: #2e3e50;
  color: #f8f9fa;
  padding: 40px 30px 80px 30px;
  border-radius: 0px;
}

#welcome .card.active {
  background-color: white;
  border: 1px solid #ffc000;
  color: #2e3e50;
  padding: 40px 30px 80px 30px;
}

.card-header {
  font-weight: 900;
  font-size: 1.2rem;
  border: none;
  background-color: inherit;
}

.card-text {
  font-size: 1.2rem;
  font-weight: 500;
}
</style>
