<template>
  <div id="subscribe">
    <div class="container width-80">
      <h4>Don't miss out. Stay Updated</h4>

      <form>
        <div class="form-row align-items-center">
          <div class="col-auto">
            <div class="input-group mb-2">
              <input
                type="text"
                class="form-control"
                id="inlineFormInputGroup"
                placeholder="Enter your email address"
              />
              <div class="input-group-prepend">
                <div class="btn btn-primary">SUBSCRIBE</div>
              </div>
            </div>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Subscribe',
  components: {},
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#subscribe {
  margin: 100px 0;
}

#subscribe h4 {
  font-weight: 800;
}

#subscribe form {
  width: 50%;
  margin: 20px auto;
}

#subscribe .form-control {
  background-color: #f8f8f8;
  border: none;
  padding: 20px;
  border-top-left-radius: 40px;
  border-bottom-left-radius: 40px;
}

#subscribe .form-control:focus {
  border: none;
  box-shadow: none;
}

#subscribe .input-group-prepend {
  background-color: #f8f8f8;
  border: none;
  padding: 6px;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 40px;
}

#subscribe .input-group-prepend .btn-primary {
  border: none;
  padding: 20px;
  border-radius: 40px;
  border-radius: 40px;
  font-weight: 800;
  width: 160px;
}
</style>
