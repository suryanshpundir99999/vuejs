<!-- modifiers -->
<!--  1 trim -->
<!-- 2 lazy -->
<template>
    <div>
------------------------------------------ 
   <h1>hi i am form Form_modiefier</h1>

   data modifiers : <input type="text" placeholder="name" v-model.trim="data">
   
   <h1>{{data}}</h1>


</div>

<div>
    ,nfisol
</div>
</template>

<script>
export default
{
    name:'form_modiefier',
    data()
    {
        return{
            data:""
        }
    }

}



</script>


