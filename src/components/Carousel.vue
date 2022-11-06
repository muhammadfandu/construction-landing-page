<template>
  <div id="carousel" class="carousel slide" data-bs-ride="false">
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://picsum.photos/id/122/1200/500"
          class="d-block w-100"
          alt="https://picsum.photos/1200/500"
        />
        <div class="carousel-caption d-none d-md-block">
          <h1><font color="#ffc000">Construction </font>Free PSD Template</h1>
          <p>
            Construction Bootstrap Template is a responsive, clean and modern
            designed HTML5 template for landing pages.
          </p>

          <button class="btn btn-primary">READ MORE</button>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://picsum.photos/id/122/1200/500"
          class="d-block w-100"
          alt="https://picsum.photos/1200/500"
        />
        <div class="carousel-caption d-none d-md-block">
          <h1><font color="#ffc000">Construction </font>Free PSD Template</h1>
          <p>
            Construction Bootstrap Template is a responsive, clean and modern
            designed HTML5 template for landing pages.
          </p>

          <button class="btn btn-primary">READ MORE</button>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://picsum.photos/id/122/1200/500"
          class="d-block w-100"
          alt="https://picsum.photos/200/100"
        />
        <div class="carousel-caption d-none d-md-block">
          <h1><font color="#ffc000">Construction </font>Free PSD Template</h1>
          <p>
            Construction Bootstrap Template is a responsive, clean and modern
            designed HTML5 template for landing pages.
          </p>

          <button class="btn btn-primary">READ MORE</button>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>

<script>
export default {
  name: 'Carousel',
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.carousel h1 {
  font-weight: 900;
  font-size: 4rem;
}

.carousel-caption {
  bottom: 20%;
  width: 600px;
  margin-left: auto;
  margin-right: auto;
}

#carousel .btn-primary {
  margin-top: 40px;
  font-weight: 700;
  font-size: 1rem;
  background-color: #ffc000;
  border: 1px solid #ffc000;
  width: 240px;
  height: 50px;
  border-radius: 30px;
}
</style>
