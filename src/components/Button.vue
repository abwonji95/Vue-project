<template>
    <button class="btn">{{title}}</button>
</template>

<script lang="ts">

export default {
 name:'Button',
    props:{
        title:String,
        color:String,

    },
}
</script>
<style>
.btn{
    font-size:14px;
    height:70px;
    width:160px;
    color:#ffffff;
    border-radius:10px;
    background-color: black;
    padding: 2em;
}

</style>