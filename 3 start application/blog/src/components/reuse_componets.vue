<template>
    <div>
      <h1>reuse components</h1>
      <ul>
        <li v-for="item in userss" :key="item.name">
            
            <user :data="item" />


        </li>
      </ul>
    </div>
  </template>
  
  <script>
  import user from './user.vue'

  
  export default {
    name: 'reuse-components',
  
    components: {
      user
    },
  
    data() {
      return {
        userss: [
          {
            name: 'anil',
            email: 'suryanshpundir@99.com'
          },
          {
            name: 'depu',
            email: 'depu88@.com'
          },
          {
            name: 'surya',
            email: 'surya88@.com'
          },
          {
            name: 'tanu',
            email: 'tanu88@.com'
          }
        ]
      }
    }
  }
  </script>
  