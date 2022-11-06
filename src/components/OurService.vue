<template>
  <div id="our-service">
    <div class="container-fuid">
      <div class="row">
        <div class="col-6">
          <img
            src="https://picsum.photos/1200/900"
            class="d-block w-100"
            alt="https://picsum.photos/1200/900"
          />
        </div>
        <div class="col-6">
          <div class="row mt-4 mx-4 px-4">
            <h2 class="float-left text-left mx-4"><b>Our Service</h2>

            <div class="col-3 mt-2">
              <button class="btn btn-secondary btn-round">
                <i class="fa fa-cogs"></i>
              </button>
            </div>
            <div class="col-9 mt-2">
              <h6 class="mt-4 text-left font-weight-bold">
                <b>REPAIR SERVICES</b>
              </h6>
              <p class="text-left font-weight-bold mt-3">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt
              </p>
            </div>

            <div class="col-3">
              <button class="btn btn-secondary btn-round">
                <i class="fa fa-cogs"></i>
              </button>
            </div>
            <div class="col-9">
              <h6 class="mt-4 text-left font-weight-bold">
                <b>WALL PAINTING</b>
              </h6>
              <p class="text-left font-weight-bold mt-3">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt
              </p>
            </div>

            <div class="col-3">
              <button class="btn btn-secondary btn-round">
                <i class="fa fa-cogs"></i>
              </button>
            </div>
            <div class="col-9">
              <h6 class="mt-4 text-left font-weight-bold">
                <b>PREMIUM SUPPORT</b>
              </h6>
              <p class="text-left font-weight-bold mt-3">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid margin-y-100">
      <div class="statistics-background"></div>
      <div class="container statistics-content">
        <div class="row">
          <div class="col-3">
            <h4>Completed Project</h4>
            <h1>2641</h1>
          </div>
          <div class="col-3">
            <h4>Material Use</h4>
            <h1>6641</h1>
          </div>
          <div class="col-3">
            <h4>Work People</h4>
            <h1>10641</h1>
          </div>
          <div class="col-3">
            <h4>Happy CLients</h4>
            <h1>2434</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'OurService',
  components: {},
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#our-service {
  margin: 100px 0;
}

.margin-y-100 {
  margin: 100px 0;
}

.statistics-background {
  background-image: url(https://picsum.photos/1600/244);
  filter: brightness(60%);

  position: absolute;
  left: 0;
  right: 0;
  z-index: 1;
  display: block;
  width: 100vw;
  height: 200px;
}

.statistics-content {
  color: white;
  padding: 50px 0;

  position: absolute;
  left: 0;
  right: 0;
  z-index: 9999;
  margin-left: 20px;
  margin-right: 20px;
  overflow: hidden;
}

</style>
