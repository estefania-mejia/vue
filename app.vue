<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <CarComposition :costo="costo" />
  
</template>

<script>
import CarComposition from "./components/CarComposition";


export default {
  components:{
    CarComposition,
  },

    setup() {
      let costo = 30;

      return{
        costo,
      };
    },
};

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

