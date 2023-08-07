
<template>

    <h1> learn Events</h1>
    <button v-on:click="test()">click me</button>

</template>


<script>
export default {
  name: 'Event-s',

  methods:
  {
    test()
    {
        alert("function called")
    }

  }
  
}
</script>


<style scoped>

button{
    height: 20px;
    background-color: cadetblue;
}

</style>