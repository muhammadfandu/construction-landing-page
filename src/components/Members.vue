<template>
  <div id="members">
    <div class="container my-4 px-4">
      <div class="text-center">
        <span class="welcome-span">We offer</span>
        <h1 class="welcome-header">
          <font color="#ffc000">Team </font>Members
        </h1>
        <p class="welcome-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation
        </p>
      </div>

      <div class="container width-80">
        <div class="row my-4">
          <div class="col-4">
            <div class="card">
              <img
                src="https://picsum.photos/id/125/200/200"
                class="d-block img-profile"
                alt="https://picsum.photos/200/200"
              />
              <h4 class="card-header">TIMOTHY REID</h4>
              <p class="card-text">Project Manager</p>
              <div class="social-icon-wrapper">
                <div class="social-icon">
                  <i class="fa fa-facebook"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-twitter"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-youtube"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-instagram"></i>
                </div>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card">
              <img
                src="https://picsum.photos/id/142/200/200"
                class="d-block img-profile"
                alt="https://picsum.photos/200/200"
              />
              <h4 class="card-header">MARTHA DOE</h4>
              <p class="card-text">Project Manager</p>
              <div class="social-icon-wrapper">
                <div class="social-icon">
                  <i class="fa fa-facebook"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-twitter"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-youtube"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-instagram"></i>
                </div>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card">
              <img
                src="https://picsum.photos/id/455/200/200"
                class="d-block img-profile"
                alt="https://picsum.photos/200/200"
              />
              <h4 class="card-header">ROBIUL SIDDIKE</h4>
              <p class="card-text">Project Manager</p>
              <div class="social-icon-wrapper">
                <div class="social-icon">
                  <i class="fa fa-facebook"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-twitter"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-youtube"></i>
                </div>
                <div class="social-icon">
                  <i class="fa fa-instagram"></i>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Members',
  components: {},
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#members {
  margin: 100px 0;
}

.img-profile {
  width: 120px;
  height: 120px;
  margin: 20px auto 40px auto;
  border-radius: 60px;
}

#members .card {
  background-color: #2e3e50;
  color: #f8f9fa;
  padding: 40px 30px 80px 30px;
  border-radius: 0px;
}

#members .card-header {
  font-weight: 900;
  font-size: 1.2rem;
  border: none;
  background-color: inherit;
}

#members .card-text {
  font-size: 1.2rem;
  font-weight: 500;
  color: #ffc000;
}

.social-icon-wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

.social-icon {
  background-color: #eee;
  color: #333;
  padding: 10px;
  width: 40px;
  height: 40px;
}
</style>
