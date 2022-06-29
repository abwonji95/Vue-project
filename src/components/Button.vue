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
    height:40px;
    width:60px;
    color:#34125c
}

</style>