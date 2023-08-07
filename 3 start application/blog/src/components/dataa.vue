<template>
<h1> exaple of data </h1>
name {{fullname }}
phone no {{phoneno }}
email {{ email }}

</template>


<script>

export default
{
    name: 'dat-aa' ,
    data()
    {
        return{     // you have to write { these syntx here otherwise it give an error 
            fullname : 'suryansh pundir',
            phoneno : '8445006926',
            email : 'suryanshpundir999@gmail.com'
        }
    }
}


</script>