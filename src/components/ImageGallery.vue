<template>
  <div class="image-gallery">
    <div class="container">
      <div class="row">
        <div class="col-lg-2">
          <img
            src="@/assets/men-wear.png"
            alt="Men Wear"
            class="img-fluid rounded-circle"
          />
        </div>
        <div class="col-lg-2">
          <img
            src="@/assets/women-wear.png"
            alt="Women Wear"
            class="img-fluid rounded-circle"
          />
        </div>
        <div class="col-lg-2">
          <img
            src="@/assets/winter-wear.png"
            alt="Winter Wear"
            class="img-fluid rounded-circle"
          />
        </div>
        <div class="col-lg-2">
          <img
            src="@/assets/hooded-tshirt.png"
            alt="Hooded Tshirt"
            class="img-fluid rounded-circle"
          />
        </div>
        <div class="col-lg-2">
          <img
            src="@/assets/polo-neck-tshirt.png"
            alt="Polo Neck Tshirt"
            class="img-fluid rounded-circle"
          />
        </div>
        <div class="col-lg-2">
          <img
            src="@/assets/full-sleeve-tshirt.png"
            alt="Full Sleeve Tshirt"
            class="img-fluid rounded-circle"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ImageGallery",
};
</script>

<style scoped>
.image-gallery {
  margin-top: 20px;
}

.img-fluid {
  max-width: 100%;
  height: auto;
  margin-left: 10px;
}
</style>
