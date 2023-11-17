<template>
  <header class="header">
    <div class="container">
      <div class="brand">
        <a href="#" class="navbar-brand">Welcome to Our Store Hiscraves</a>
      </div>
      <div class="contact-info">
        <span class="call-icon">
          <i class="fas fa-phone"></i>
        </span>
        <span class="call-us">Call Us: 1234567890</span>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style scoped>

.header {
  background-color: #000;
  color: #fff;
  padding: 10px 0;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: left;
}

.navbar-brand {
  color: #fff;
  text-decoration: none;
  font-size: 18px;
}

.contact-info {
  display: flex;
  align-items: center;
}

.call-us {
  color: #fff;
  margin-left: 15px;
}

.call-icon {
  margin-left: 20px;
}

</style>
