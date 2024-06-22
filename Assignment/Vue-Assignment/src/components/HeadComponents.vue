<template>
    <div class="header">
        <div class="title">
            <h3>Best City Guide</h3>
        </div>
        <div class="menu">
            <ul>
                <li>ICE CREAM</li>
                <li>DONUTS</li>
                <li>TEA</li>
                <li>COFFEE</li>
            </ul>
        </div>
    </div>
</template>

<style scope>
    .header{
        width: 100%;
        height: 60px;
    }
    .title{
        float: left;
        margin-left: 20px;
    }
    .menu{
       float:right;
    }
    ul{
        display: flex;
    }
    li{
        list-style-type: none;
        /* margin-left: 30px; */
        margin-right: 5rem;
        margin-top: 8px;
        color:rgb(1, 221, 221);
        font-weight: bold;
    }
</style>