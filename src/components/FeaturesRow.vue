<!-- src/components/ImageRow.vue -->
<template>
  <div class="feature-row" style="background-color: #f5f4f2">
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <img
            src="@/assets/features/7-day-return.png"
            alt="Image 1"
            class="img-fluid"
          />
        </div>
        <div class="col-md-3">
          <img
            src="@/assets/features/quality-products.png"
            alt="Image 1"
            class="img-fluid"
          />
        </div>
        <div class="col-md-3">
          <img
            src="@/assets/features/safe-payment.png"
            alt="Image 1"
            class="img-fluid"
          />
        </div>
        <div class="col-md-3">
          <img
            src="@/assets/features/24-7-helpline.png"
            alt="Image 1"
            class="img-fluid"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SemiCircle from './SemiCircle.vue';

export default {
    components: SemiCircle
}
</script>

<style scoped>
/* Add your component-specific styles here */


.feature-row {
  margin-top: 20px;
  padding: 20px 0;
  overflow: hidden;
  position: relative;
}

.img-fluid {
  /* margin-right: 100px; */
  width: 50%;
  height: auto;
}
</style>
