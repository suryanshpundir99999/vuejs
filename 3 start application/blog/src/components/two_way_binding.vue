<template>

    <h1> two way binding example are</h1>
 
    type here<input type="text"  v-model="count">

    {{ count }}

</template>

<script>
export default

{
    name: 'two_way_binding' ,

    data()
    {
        return {

            count : 0
                   

        }
    }

   
}

</script>
