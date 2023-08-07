<template>
    <h1>hi its me home componets my string len is{{ "home".length}}</h1>
    <ul><li>
    email {{ email }} </li>
    <li> phone{{ phoneno }} </li>
    <li>university {{university()}}</li>
</ul>
</template>

<script>

export default
{
   name: 'home-componet',
   data()
   {
    return{
        email:'suryanshpundir999@gmail.com',
        phoneno: '8445000696',
        university: function()
        {
            return("quantum university roorkee")
        }
    }
   }
}

</script>


<style scoped>

h1
{
    background-color: aqua;
}

</style>