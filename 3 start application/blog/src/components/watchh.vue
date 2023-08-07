<template>
    <h1>example of watch</h1>

    <button v-on:click="count=count+1">+</button>
    <button v-on:click="count=count-1">-</button>
    <br>
    <div class="tom">
    {{ count }}
    </div>

</template>

<script>
export default{
    name:"wat-chh",
    data()
    {
        return{
            count:0,
             
        }
    },
    watch:{ 
        count(val){
                 if(val==10)
                 {
                    alert("limit is over please keep away")
                 }
        }

    }
}


</script>

<style scoped>

.tom{
    color: red;
    font-size: 50px;
    text-align: left;
}

</style>