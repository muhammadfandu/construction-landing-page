<template>
  <div id="testimonials">
    <div class="container my-4 px-4">
      <div class="text-center">
        <span class="welcome-span">We offer</span>
        <h1 class="welcome-header">
          <font color="#ffc000">Client </font>Testimonials
        </h1>
        <p class="welcome-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation
        </p>
      </div>
    </div>

    <div class="container width-80">
      <div class="card">
        <div class="row">
          <div class="col-2">
            <img
              src="https://picsum.photos/200/200"
              class="d-block img-round"
              alt="https://picsum.photos/200/200"
            />
          </div>
          <div class="col-9">
            <h6 class="mx-4 profile-header-name">
              <b>JOHN DOE</b>
            </h6>
            <p class="mx-4 text-left font-weight-bold">PROJECT OWNER</p>
          </div>
        </div>
        <div class="row mt-4">
          <p class="text-left text-description">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur
          </p>

          <div class="star-wrapper">
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Testimonial',
  components: {},
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#testimonials {
  padding: 100px 0;
  background-color: #f4f4f3;
}

#testimonials .card {
  background-color: #fff;
  color: #333;
  padding: 30px 80px 70px 80px;
  border-radius: 8px;
  border: none;
  box-shadow: 4px 4px 16px #88888833;
  width: 90%;
  margin: 50px auto 0px auto;
}

.profile-header-name {
  margin-top: 50px;
  text-align: left;
  font-weight: 800;
  font-size: 1.4rem;
}

.text-description {
  font-size: 1.1rem;
  line-height: 1.7;
  width: 90%;
}

.img-round {
  width: 120px;
  height: 120px;
  margin: 20px;
  border-radius: 60px;
}

.star-wrapper {
  color: #ffc000;
  text-align: left;
}

.star-wrapper i {
  margin: 0 10px;
}
</style>
