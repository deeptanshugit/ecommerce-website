<template>
  <h2 class="title"> {{ title }} </h2>
</template>

<script>
export default {
  props: {
    title: {
      type: String, 
      default: "" 
    }
  },
};
</script>


<style scoped>
.title{
  position: relative;
  max-width: 500px;
  margin: 40px auto;
  text-align: center;
  font-family: 'Playfair Display';
  font-weight: 600;
}

.title:before{
  content:" ";
  height: 2px;
  width: 130px;
  background: #FFC7D1;
  display: block;
  position: absolute;
  top: 50%;
  left: 0;
}

.title:after{
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
