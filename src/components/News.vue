<template>
  <div id="news">
    <div class="container my-4 px-4">
      <div class="text-center">
        <span class="welcome-span">We offer</span>
        <h1 class="welcome-header">
          <font color="#ffc000">World </font>News Construction
        </h1>
        <p class="welcome-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation
        </p>
      </div>
    </div>

    <div class="container width-80">
      <div class="row">
        <div class="col-4">
          <div class="card" style="width: 18rem">
            <img
              class="card-img-top"
              src="https://picsum.photos/400/350"
              alt="Card image cap"
            />
            <div class="card-body text-left">
              <h5 class="card-title">
                The Intersection Where Blockchain Meets Energy
              </h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt
              </p>
              <div class="card-footer">
                <span href="">01 Jan</span>
                <span href="">Read more</span>
              </div>
            </div>
          </div>
        </div>

        <div class="col-4">
          <div class="card" style="width: 18rem">
            <img
              class="card-img-top"
              src="https://picsum.photos/400/350"
              alt="Card image cap"
            />
            <div class="card-body text-left">
              <h5 class="card-title">
                The Intersection Where Blockchain Meets Energy
              </h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt
              </p>
              <div class="card-footer">
                <span href="">01 Jan</span>
                <span href="">Read more</span>
              </div>
            </div>
          </div>
        </div>

        <div class="col-4">
          <div class="card" style="width: 18rem">
            <img
              class="card-img-top"
              src="https://picsum.photos/400/350"
              alt="Card image cap"
            />
            <div class="card-body text-left">
              <h5 class="card-title">
                The Intersection Where Blockchain Meets Energy
              </h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt
              </p>
              <div class="card-footer">
                <span href="">01 Jan</span>
                <span href="">Read more</span>
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
  name: 'News',
  components: {},
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#news {
  margin: 100px 0;
}

#news .card {
  background-color: #ffc000;
  color: white;
  border-radius: 0;
  border: none;
}

#news .card-body {
  padding: 20px 30px;
}

#news .card-title {
  font-weight: 700;
  font-size: 1rem;
}

#news .card-text {
  font-weight: 500;
  font-size: 1rem;
}

.card-footer {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background: inherit;
  border: none;
  color: #333;
  font-size: 0.9rem;
  padding: 0;
}
</style>
