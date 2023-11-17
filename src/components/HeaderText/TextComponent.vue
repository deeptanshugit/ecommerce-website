<template>
  <h2 class="hr-lines"> {{ title }} </h2>
</template>

<script>
export default {
  props: {
    title: {
      type: String, // Specify the prop type
      default: "" // Set a default value if needed
    }
  },
};
</script>


<style scoped>
.hr-lines{
  position: relative;
  max-width: 500px;
  margin: 40px auto;
  text-align: center;
  font-family: 'Playfair Display';
  font-weight: 600;
}

.hr-lines:before{
  content:" ";
  height: 2px;
  width: 130px;
  background: #FFC7D1;
  display: block;
  position: absolute;
  top: 50%;
  left: 0;
}

.hr-lines:after{
  content:" ";
  height: 2px;
  width: 130px;
  background: #FFC7D1;
  display: block;
  position: absolute;
  top: 50%;
  right: 0;
}

</style>
