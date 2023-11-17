<template>
  <div class="image-section">
    <div class="container">
      <div class="row">

        <div class="featured-above">
          <div class="col-lg-6">
            <img
              src="@/assets/featured/baggy.png"
              alt="Large Image 1"
              class="img-fluid"
            />
          </div>
          <div class="col-lg-6">
            <img
              src="@/assets/featured/winter-collection.png"
              alt="Large Image 2"
              class="img-fluid"
            />
          </div>
        </div>

        <div class="featured-lower">
          <div class="col-lg-4">
            <img
              src="@/assets/featured/women-wear.png"
              alt="Small Image 1"
              class="img-fluid"
            />
          </div>
          <div class="col-lg-4">
            <img
              src="@/assets/featured/best-deal.png"
              alt="Small Image 2"
              class="img-fluid"
            />
          </div>
          <div class="col-lg-4">
            <img
              src="@/assets/featured/trendy.png"
              alt="Small Image 3"
              class="img-fluid"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FeaturedSection",
};
</script>

<style scoped>
.image-section {
  margin-top: 20px;
}

.featured-above {
  display: flex;
  gap: 10px;
}

.featured-lower {
  margin-top: 10px;
  display: flex;
  gap: 10px;
}

.img-fluid {
  width: 100%;
  height: auto;
}
</style>
