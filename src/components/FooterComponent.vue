<!-- src/components/Footer.vue -->
<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <!-- First Column -->
        <div class="col-md-3">
          <div class="footer-column-1">
            <p class="footer-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </p>
            <div class="social-icons">
              <!-- Add your social media icons or links here -->
              <i class="fab fa-facebook"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-instagram"></i>
              <!-- Add more icons as needed -->
            </div>
          </div>
        </div>

        <!-- Second Column -->
        <div class="col-md-3">
          <div class="footer-column">
            <h4>Online Shopping</h4>
            <ul>
              <li><a href="#">Men's Fashion</a></li>
              <li><a href="#">Women's Fashion</a></li>
              <li><a href="#">Electronics</a></li>
              <li><a href="#">Home & Furniture</a></li>
              <li><a href="#">Sports & Outdoors</a></li>
            </ul>
          </div>
        </div>

        <!-- Third Column -->
        <div class="col-md-3">
          <div class="footer-column">
            <h4>Customer Policies</h4>
            <ul>
              <li><a href="#">Shipping & Delivery</a></li>
              <li><a href="#">Returns & Exchanges</a></li>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Terms & Conditions</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
        </div>

        <!-- Fourth Column -->
        <div class="col-md-3">
          <div class="footer-column">
            <h4>Store Information</h4>
            <p>
              <i class="fa-solid fa-location-dot"></i>  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do
            </p>
            <p><i class="fas fa-phone"></i> Phone: 123-456-7890</p>
            <p>
              <i class="fa-regular fa-envelope"></i> Email: info@example.com
            </p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer-text {
  text-align: start;
}
.footer {
  margin-top: 40px;
  background-color: #ffffff;
  color: #000000;
  padding: 30px 0;
}

.footer-column {
  margin-bottom: 20px;
}

.social-icons {
  display: flex;
  gap: 40px;
}

.social-icons i {
  margin-right: 10px;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  margin-bottom: 10px;
  text-align: start;
}

a {
  color: #000000;
  text-decoration: none;
  /* margin-left: 10px; */
}

p {
  text-align: start;
}

h4 {
  color: #770015;
    text-align: start;
}
</style>
