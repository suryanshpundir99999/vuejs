<!-- here just we make the method function -->

<template>

    <h1> EXAMPLE OF METHODE</h1>

    <h2> from method <h3> {{getname("suryansh")}} </h3>
        <h3> {{getname("divyansh")}}</h3>
        <h3>full data {{ normaldata().age}}</h3>
    
    </h2>

</template>

<script>
export default
{
    name:"metho-dss",
    methods:{
        getname(yname)
        {
            return yname  

        } ,
        normaldata()
        {
            return {
            name:'manu', 
            age : 40,
            email : 'abc@xyz'
            }
        }

    }
}
</script>