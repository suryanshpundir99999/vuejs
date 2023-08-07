<template>
<h1>simple form example </h1>
<form>
    <label for="email">email</label>
    <input type="email" placeholder="email" v-model="form.email">

    <label for="password">email</label>
    <input type="password" placeholder="password" v-model="form.password">

<br><br>
<h1>conutry</h1>
<select v-model="form.conutry">
    <option>india</option>
    <option>china</option>
    <option>usa</option>
</select>
<br><br>

<h1>technology</h1>
<select v-model="form.technology">
    <option>java script</option>
    <option>java</option>
    <option>css</option>
</select>
<br><br>

<h1>Gender</h1>

<label for="Male">Male</label>
<input type="radio" value="male" v-model="form.gender">

<label for="Female">Female</label>
<input type="radio" value="female" v-model="form.gender">

<button v-on:click="login">click me</button>
</form>
{{ form }}

</template>

<script>
export default {
    name: 'simple-form',

    data() {
        return {
            form: {
                email: "",
                password: "",
                conutry: "",
                technology: "",
                gender: [],

            },
            error:[],
        }
    },
    methods: {
        login() {
          this.error = [];
            for(const item in this.form)
            {
              if(this.form[item]==="" || this.form[item.length===0] )
              {
                 this.error.push(item)
              } 
            }
            if(this.error===0)
              {
                alert("data submitted")
              }
            console.warn("login data", this.form);
        }
    }
}
</script>
