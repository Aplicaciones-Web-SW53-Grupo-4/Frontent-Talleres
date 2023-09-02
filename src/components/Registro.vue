<template>
  <div class="container">
    Registro{{ name }}
  </div>
</template>

<script>
export default {
  props: {
    name: String,
  },
  name:"Registro",
};
</script>

<style scoped>
.container {
  margin: 2px;
  background-color: black;
  font-size: 50px;
  color: #f2f2f2;
  padding: 6px;
  text-align: center;
  border-radius: 30px;
}

.container:hover {
  background-color: red;
}
</style>
