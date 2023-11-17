<!-- src/components/SubscribeSection.vue -->
<template>
  <div class="subscribe-section">
    <div class="container">
      <div class="subscribe-container">

        <div class="gradient-rectangle"></div>

        <p class="subscribe-text">
          Subscribe to get updates on exciting offers & deals
        </p>

        <!-- Subscription input box -->
        <div class="subscribe-input">
          <input
            type="email"
            placeholder="Enter your email"
            class="form-control"
          />
          <button class="btn btn-primary">Subscribe</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Add your component-specific styles here */
.subscribe-section {
  margin-top: 20px;
}

.gradient-rectangle {
  width: 100%;
  height: 300px;
  background: linear-gradient(to left, #770015, #d56161);
}

.subscribe-container {
  position: relative;
}

.subscribe-text {
  position: absolute;
  top: 35%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #fff;
  font-size: 38px;
  text-align: center;
  font-family: 'Playfair Display';
}

.subscribe-input {
  position: absolute;
  bottom: 60px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  align-items: center;
}

.subscribe-input input {
  flex: 1;
  padding: 10px;
  border: none;
  border-radius: 5px 0 0 5px;
}

.subscribe-input button {
  padding: 10px 20px;
  border: none;
  border-radius: 0 5px 5px 0;
  background-color: #770015;
  color: #fff;
}
</style>
