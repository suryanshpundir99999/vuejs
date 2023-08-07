
<!-- making check box with label -->
<!-- make ras=dio button with label -->
<!-- define data properties -->
<!-- apply two way binding -->


<template>
    <h1>making check box </h1>
<label for="java">java</label>
<input type="checkbox"  value="java" id="java" v-model="technology">

<label for="php">php</label>
<input type="checkbox"  value="php" id="php" v-model="technology">


<label for="node">node</label>
<input type="checkbox"  value="node" id="node" v-model="technology">


<br> 
<h2>your out put is : {{ technology }}  {{ circle }} </h2>

<h3>lets make radio button</h3>

<label for="student">student</label>
<input type="radio" value="student" id="student" v-model="circle">

<br><label for="teacher">teacher</label> 
<input type="radio" value="teacher" id="teacher" v-model="circle">

</template>


<script>

export default
{
    name:'getcheck-boxradio',
    data()
    {
        return{
            technology:[],
            circle:null,
        }
        
    }

}

</script>