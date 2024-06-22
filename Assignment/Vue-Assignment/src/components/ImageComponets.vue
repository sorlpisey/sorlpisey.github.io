<template>
   <div :style="{backgroundColor:backColor}" class="background">
    <img  :src=" image" >
    <h1 :style="{color:Color}">The Best City</h1>
    <h4 :style="{color:Color}">The best drinks and eats in the best city ever.</h4>
   </div>
</template>
<script>
 export default {
    data(){
        return{
            image:"../src/assets/city.svg",
            backColor:" aqua",
            Color:"white",
        }

    },

 };
</script>

<style scope>
   img{
      width: 15%;
      height: 35%;
      margin-left: 48rem;
      margin-top: 4rem;
   }
   .background{
      width: 100%;
      height: 430px;
   }
   h1{
      margin-left: 51rem;
   }
   h4{
      margin-left: 43rem;
      font-size: 25px;
   }
</style>