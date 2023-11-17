<template>
  <div>
    <ProductSection></ProductSection>
  </div>
</template>

<script>
import ProductSection from './ProductSection/ProductSection.vue';
export default {
  components: {
    ProductSection,
  },
  name: "ProductComponent",
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
/* Add your component-specific styles here */
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
  background-color: rgba(255, 255, 255, 0.9);
  border-radius: 50%;
  padding: 10px;
  visibility: hidden;
  opacity: 0;
  transition: visibility 0s, opacity 0.5s linear;
}

.circle-icons i {
  cursor: pointer;
}

.product-item:hover .img-fluid {
  filter: blur(5px);
}

.product-item:hover .circle-icons {
  visibility: visible;
  opacity: 1;
}
</style>
