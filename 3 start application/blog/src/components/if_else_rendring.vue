
<!-- write html code for show and hide ::::  here we use v-if    to hide and show the data-->
<!-- apply if else condition -->
<!-- if and else condition with button click -->

<template>
<h1 v-if="show">learn v-if</h1>
lets take the exaple of button

<button v-on:click="show=!show" >click me </button>     <!--here we implemet how we toogle the code-->

</template>


<script>
 
export default
{
    name:'if_else_rendring',
    data(){
        return{
            show:true,
                   
        }
    }

}  

</script>