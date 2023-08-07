<template>
    <div>
      <h1>user components</h1>
            name: 'anil',
            name: 'anil',
      {{data.name}}
    </div>
  </template>
  
  <script>

  export default {
    name:'user',
    props:{
      data:Object
    }
  }
  </script>
  