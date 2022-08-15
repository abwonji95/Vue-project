<script  lang="ts">
import { ref, reactive } from '@vue/reactivity';


const name=ref('maranatha')
const age=reactive({count:10})
export default{
    name:'Counter',
    props:{
        name:String,
        age:Number,

    },
}

</script>

<template>
<div class="div">
    <h1>Name : {{name}}</h1>
    <h2>age : {{age.count}}</h2>
</div>

</template>
