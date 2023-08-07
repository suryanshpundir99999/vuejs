
<template>

    <h1>learn how to take input</h1>
   
    name : <input type="text" placeholder="name" v-model="namee">

    age : <input type="text" placeholder="age" v-model="agee">



your name is {{ namee }}
your age is  {{ agee }}

</template>

<script>

export default
{
    name:'taking-input',

    data()
    {
        return{

            namee:null,
            agee: null,
                        
        }
    }  
  
}


</script>