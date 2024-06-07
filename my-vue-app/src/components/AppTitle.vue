<script>
export default {
  data(){

return {
  message: "La mia prima app di vue"
}
}
};

</script>

<template>


    <h1 class="textColor">{{ message }}</h1>
  

</template>

<style scoped>
  
.textColor {
  color: red;
  text-transform: capitalize;
  
}
h1 {
  font-size: 5.5rem;
  line-height: 1.1;
}


</style>
