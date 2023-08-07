<!--  slots is very good -->
<!--  to used to send data to parents data -->
<!-- here we create slot in this file and used it in childd file -->
<template>
<h1>example of slots</h1>
<childd> hi i come from slots </childd>
<childd> <h1> its esay to use</h1></childd>

</template>

<script>
import childd from './childd.vue';
export default
{
    name:'slot-ss',
    components:{
        childd
    }
}


</script>