<!-- ref is used to set or get data or many information .... -->

<template>

    <h1>exapmle of reff</h1>

    input <input type="text" ref="input">
    <button v-on:click="getdata"> click me</button>

</template>

<script>

export default
{
    name:'re-ff',

    methods:{
        getdata()
        {
             this.$refs.input.focus()
              this.$refs.input.style.color="red"
              let a = this.$refs.input.value
                console.log(a)
        }
    }
    
}

</script>