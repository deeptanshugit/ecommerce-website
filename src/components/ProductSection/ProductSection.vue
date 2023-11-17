<!-- src/components/ProductComponent.vue -->
<template>
  <div class="product-section">
    <div class="container">
      <div class="row">
        <!-- Repeat the following block for each product -->
        <div class="col-lg-3 col-md-4 col-sm-6">
          <div
            class="product-item"
            @mouseover="showIcons"
            @mouseleave="hideIcons"
          >
            <!-- Product Image (200x400) -->
            <div class="image-container">
              <img
                src="@/assets/product/product-1.png"
                alt="Product Image 1"
                class="img-fluid"
              />
              <!-- Circle icons -->
              <div v-show="hovered" class="circle-icons">
                <div class="circle-icon" @click="addToCart">
                  <i class="fa-solid fa-cart-shopping"></i>
                </div>
                <div class="circle-icon" @click="addToFavorites">
                  <i class="fa-solid fa-heart"></i>
                </div>
                <div class="circle-icon" @click="shareProduct">
                  <i class="fa-solid fa-square-share-nodes"></i>
                </div>
              </div>
            </div>

            <!-- Product Description -->
            <p class="product-description">
              Men Henley Neck Full Sleeve Red Wine
            </p>

            <!-- Product Pricing -->
            <p class="product-pricing">
              <span>₹399</span>
              <span class="original-price">₹499</span>
            </p>

            <!-- Size Buttons -->
            <div class="size-buttons">
              <button class="btn btn-outline-secondary mr-5">S</button>
              <button class="btn btn-outline-secondary">M</button>
              <button class="btn btn-outline-secondary">L</button>
              <button class="btn btn-outline-secondary">XL</button>
              <button class="btn btn-outline-secondary">XXL</button>
            </div>
          </div>
        </div>

        <div class="col-lg-3 col-md-4 col-sm-6">
          <div
            class="product-item"
            @mouseover="showIcons"
            @mouseleave="hideIcons"
          >

            <div class="image-container">
              <img
                src="@/assets/product/product-2.png"
                alt="Product Image 1"
                class="img-fluid"
              />

              <div v-show="hovered" class="circle-icons">
                <div class="circle-icon" @click="addToCart">
                  <i class="fa-solid fa-cart-shopping"></i>
                </div>
                <div class="circle-icon" @click="addToFavorites">
                  <i class="fa-solid fa-heart"></i>
                </div>
                <div class="circle-icon" @click="shareProduct">
                  <i class="fa-solid fa-square-share-nodes"></i>
                </div>
              </div>
            </div>

            <!-- Product Description -->
            <p class="product-description">
              Men Henley Neck Full Sleeve Red Wine
            </p>

            <!-- Product Pricing -->
            <p class="product-pricing">
              <span>₹399</span>
              <span class="original-price">₹499</span>
            </p>

            <!-- Size Buttons -->
            <div class="size-buttons">
              <button class="btn btn-outline-secondary">S</button>
              <button class="btn btn-outline-secondary">M</button>
              <button class="btn btn-outline-secondary">L</button>
              <button class="btn btn-outline-secondary">XL</button>
              <button class="btn btn-outline-secondary">XXL</button>
            </div>
          </div>
        </div>

        <div class="col-lg-3 col-md-4 col-sm-6">
          <div
            class="product-item"
            @mouseover="showIcons"
            @mouseleave="hideIcons"
          >

            <div class="image-container">
              <img
                src="@/assets/product/product-3.png"
                alt="Product Image 1"
                class="img-fluid"
              />

              <div v-show="hovered" class="circle-icons">
                <div class="circle-icon" @click="addToCart">
                  <i class="fa-solid fa-cart-shopping"></i>
                </div>
                <div class="circle-icon" @click="addToFavorites">
                  <i class="fa-solid fa-heart"></i>
                </div>
                <div class="circle-icon" @click="shareProduct">
                  <i class="fa-solid fa-square-share-nodes"></i>
                </div>
              </div>
            </div>

            <!-- Product Description -->
            <p class="product-description">
              Men Henley Neck Full Sleeve Red Wine
            </p>

            <!-- Product Pricing -->
            <p class="product-pricing">
              <span>₹399</span>
              <span class="original-price">₹499</span>
            </p>

            <!-- Size Buttons -->
            <div class="size-buttons">
              <button class="btn btn-outline-secondary">S</button>
              <button class="btn btn-outline-secondary">M</button>
              <button class="btn btn-outline-secondary">L</button>
              <button class="btn btn-outline-secondary">XL</button>
              <button class="btn btn-outline-secondary">XXL</button>
            </div>
          </div>
        </div>

        <div class="col-lg-3 col-md-4 col-sm-6">
          <div
            class="product-item"
            @mouseover="showIcons"
            @mouseleave="hideIcons"
          >

            <div class="image-container">
              <img
                src="@/assets/product/product-4.png"
                alt="Product Image 1"
                class="img-fluid"
              />

              <div v-show="hovered" class="circle-icons">
                <div class="circle-icon" @click="addToCart">
                  <i class="fa-solid fa-cart-shopping"></i>
                </div>
                <div class="circle-icon" @click="addToFavorites">
                  <i class="fa-solid fa-heart"></i>
                </div>
                <div class="circle-icon" @click="shareProduct">
                  <i class="fa-solid fa-square-share-nodes"></i>
                </div>
              </div>
            </div>

            <!-- Product Description -->
            <p class="product-description">
              Men Henley Neck Full Sleeve Red Wine
            </p>

            <!-- Product Pricing -->
            <p class="product-pricing">
              <span>₹399</span>
              <span class="original-price">₹499</span>
            </p>

            <div class="size-buttons">
              <button class="btn btn-outline-secondary mr-2">S</button>
              <button class="btn btn-outline-secondary mr-2">M</button>
              <button class="btn btn-outline-secondary mr-2">L</button>
              <button class="btn btn-outline-secondary mr-2">XL</button>
              <button class="btn btn-outline-secondary">XXL</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <ButtonComponent></ButtonComponent>
  </div>
</template>

<script>
import ButtonComponent from "../ButtonComponent.vue";
export default {
  name: "ProductComponent",
  components: {
    ButtonComponent,
  },
  data() {
    return {
      hovered: false,
    };
  },
  methods: {
    showIcons() {
      this.hovered = true;
    },
    hideIcons() {
      this.hovered = false;
    },
    addToCart() {
      console.log("hello");
    },
    addToFavorites() {
      console.log("hello");
    },
    shareProduct() {
      console.log("hello");
    },
  },
};
</script>

<style scoped>
.product-pricing {
  text-align: center;
  font-family: "Montserrat";
  font-size: 25px;
  font-weight: 600;
}

.product-pricing span.original-price {
  margin-left: 10px;
  text-decoration: line-through;
  color: #FF0000;
  font-size: 20px;
}

.product-description {
  margin-top: 10px;
  font-size: 15px;
  text-wrap: nowrap;
}

.btn {
  margin-right: 8px;
}
.product-section {
  margin-top: 20px;
}

.product-item {
  position: relative;
  margin-bottom: 20px;
  overflow: hidden;
}

.image-container {
  position: relative;
}

.img-fluid {
  width: 200px;
  height: 400px;
  max-width: 100%;
  height: auto;
  transition: filter 0.5s ease-in-out;
}

.circle-icons {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  justify-content: space-around;
  align-items: center;
  border-radius: 50%;
  padding: 15px;
  visibility: hidden;
  gap: 15px;
  opacity: 0;
  transition: visibility 0s, opacity 0.5s linear;
}

.circle-icon {
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background-color: #fff;
  cursor: pointer;
}

.circle-icon i {
  font-size: 20px;
  color: #000; /* Adjust icon color as needed */
}

.product-item:hover .img-fluid {
  filter: blur(5px);
}

.product-item:hover .circle-icons {
  visibility: visible;
  opacity: 1;
}
</style>
