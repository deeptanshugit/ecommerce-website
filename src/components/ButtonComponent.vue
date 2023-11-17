<template>
    <div class="button-container">
      <button class="custom-button">View All</button>
    </div>
  </template>
  
  <style scoped>
  .button-container {
    display: flex;
    justify-content: center;
    margin-top: 20px;
    margin-bottom: 40px;
  }
  
  .custom-button {
    background-color: #770015;
    color: #fff;
    padding: 10px 30px;
    font-size: 20px;
    border: none;
    /* border-radius: 5px; */
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  .custom-button:hover {
    background-color: #5c0011; /* Adjust hover color as needed */
  }
  </style>
  