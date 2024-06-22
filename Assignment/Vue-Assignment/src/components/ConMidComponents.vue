<template>
    <div class="contenmid">
        <h2>Gread Food</h2>
    </div>
    <img :src="image" class="image">
    <p class="text">Croissant Lorem Lorem ipsum dolor culpa?ipsum dolor sit amet consectetur adipisicing elit. Perferendis dicta, eveniet animi perspiciatis dolore ea placeat voluptates. Tempora quis, voluptates totam id, at dolorem, tempore rem porro amet quia magni.</p>
</template>
<script>
 export default {
    data(){
        return{
            image :"../src/assets/item.svg",
        };
    },
 };
</script>

<style scope>
    .contenmid{
        width: 30%;
        height: 300px;
        display: flex;
        margin-left: 45rem;
        margin-top: -20rem;
        font-size: 20px;
    }
    .image{
        margin-top: -14rem;
        width: 20%;
        margin-left: 45rem;
    }
    .text{
        width: 20%;
        height: 300px;
        margin-left: 45rem;
        font-size: 20px;
    }

</style>