<template>
  <div class="navbar">
    <div class="container">
      <div class="menu">
        <span class="menu-icon">
          <!-- Replace with your call icon -->
          <i class="fa-solid fa-bars"></i>
        </span>
      </div>
      <!-- Brand/logo -->
      <div class="brand">
        <!-- <img src="@/assets/logo.png" alt="Logo" height="30" /> -->
        <h5> Logo Here </h5>
      </div>

      <!-- Navbar items -->
      <ul class="nav">
        <li><i class="fa-solid fa-magnifying-glass"></i></li>
        <li><i class="fa-solid fa-heart"></i></li>
        <li><i class="fa-solid fa-bag-shopping"></i></li>
        <li><i class="fa-regular fa-user"></i></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavbarComponent",
};
</script>

<style scoped>
h5 {
  margin-top: 10px;
  text-align: center;
  font-family: 'Playfair Display';
  font-weight: 600;
}
.navbar {
  background-color: #f8f9fa; 
  padding: 10px 0;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.brand img {
  height: 30px;
}

.nav {
  list-style: none;
  display: flex;
}

.nav li {
  margin-right: 20px;
}

.nav a {
  text-decoration: none;
  color: #343a40; /* Set your desired text color */
  font-weight: bold;
  font-size: 16px;
  transition: color 0.3s ease;
}

.nav a:hover {
  color: #007bff; /* Set your desired hover color */
}
</style>
