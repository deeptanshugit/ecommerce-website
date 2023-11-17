<template>
  <div class="discount-banner">
    <div class="container">
    <div class="row">
      <!-- Rectangle 1 -->
      <div class="col-md-12 col-lg-6">
        <div class="discount-container" style="background-color: #cccea7">
          <img
            src="@/assets/discount/dimond.png"
            alt="Image 1"
            class="img-fluid"
          />
          <div class="text-container">
            <p class="hurry-up">Hurry Up</p>
            <p class="discount">85% Off</p>
            <button class="btn btn-outline-light">Shop Now</button>
          </div>
        </div>
      </div>

      <!-- Rectangle 2 -->
      <div class="col-md-12 col-lg-6">
        <div class="discount-container" style="background-color: #d6bebe">
          <img
            src="@/assets/discount/discount.png"
            alt="Image 2"
            class="img-fluid"
          />
          <div class="text-container">
            <p class="hurry-up">Hurry Up</p>
            <p class="discount">85% Off</p>
            <button class="btn btn-outline-light">Shop Now</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<style scoped>
.discount-banner {
  margin-top: 20px;
}

.discount-container {
  position: relative;
  text-align: center;
  padding: 20px;
  width: 100%;
  height: 652px;
}

.img-fluid {
  width: 172px;
  height: 172px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

.text-container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: black;
  font-family: 'Playfair Display';
  font-weight: 600;
}

.hurry-up {
  font-size: 36px;
  margin-top: 120px;
  margin-bottom: 10px;
}

.discount {
  font-size: 84px;
  font-weight: bold;
  margin-bottom: 20px;
}

.btn-outline-light {
  border-color: #fff;
  background-color: transparent;
  color: #fff;
}

.btn-outline-light:hover {
  background-color: #fff;
  color: #000;
}
</style>
