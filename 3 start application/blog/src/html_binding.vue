<template>

    <h1>---------------</h1>
    <h1>html binding</h1>
    {{ Text }}
    <div v-html="tag"/>
    <div v-html="x"/>
</template>

<script>
export default
{
    name:'html_binding',
    data()
    {
        return{
            Text:"satiii",
            tag:"<h1> suryansh pundir </h1>",
            x:"<h3>from khudana</h3>"
        }
    }
}



</script>