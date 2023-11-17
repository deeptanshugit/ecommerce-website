<!-- src/components/ImageBlurComponent.vue -->
<template>
    <div class="image-blur-section">
      <div class="container">
        <div class="row">
          <div class="col-lg-4 col-md-12">
            <div class="image-container">
              <img src="@/assets/collection/street-wear.png" alt="Rectangle Image 1" class="img-fluid">
              <div class="blur-overlay">
                <p class="collection-name">Streetwear Collections</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-12">
            <div class="image-container">
              <img src="@/assets/collection/striped.png" alt="Rectangle Image 1" class="img-fluid">
              <div class="blur-overlay">
                <p class="collection-name">Striped T-Shirts</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-12">
            <div class="image-container">
              <img src="@/assets/collection/round-neck.png" alt="Rectangle Image 1" class="img-fluid">
              <div class="blur-overlay">
                <p class="collection-name">Round Neck Tshirts</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4 col-md-12">
            <div class="image-container">
              <img src="@/assets/collection/printed.png" alt="Rectangle Image 1" class="img-fluid">
              <div class="blur-overlay">
                <p class="collection-name">Printed T-Shirts</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-12">
            <div class="image-container">
              <img src="@/assets/collection/oversized.png" alt="Rectangle Image 1" class="img-fluid">
              <div class="blur-overlay">
                <p class="collection-name">Oversized T-Shirts</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-12">
            <div class="image-container">
              <img src="@/assets/collection/half-sleeve.png" alt="Rectangle Image 1" class="img-fluid">
              <div class="blur-overlay">
                <p class="collection-name">Half Sleeves T-Shirt</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  /* Add your component-specific styles here */
  .image-blur-section {
    margin-top: 20px;
  }
  
  .image-container {
    position: relative;
    overflow: hidden;
  }
  
  .img-fluid {
    width: 100%;
    height: 100%;
    max-width: 100%;
    height: auto;
  }
  
  .blur-overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 20%;
    backdrop-filter: blur(30px);
  }

  .collection-name {
    margin-top: 20px;
    color: aliceblue;
    font-size: 36px;
  }
  </style>
  