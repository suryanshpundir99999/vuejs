<!-- child file -->

<template>

{{ name }}
{{ getdata }}


</template>

<script>
export default
{
    name:'chi-ld',
    props:{
        name:String,
        post:String,
        getdata : Function,
    }
}

</script>