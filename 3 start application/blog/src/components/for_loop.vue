<template>
<h1>----------------------------------------------------------</h1>
learn for loop<br>
define array in data property<br>
apply loop on it<br>
define array of an object in data properties<br>
apply loop on it <br>

start:

<!-- use for loop to rendring the data -->

<ul>
    <li v-for="item in loop" :key="item">

        {{ item }}

    </li>
</ul>
<!-- examople of using for loop in object array -->
out put by for loop using object array
<ul>
    <li v-for="x in obje" :key="x.name">
         {{ x.name }} and the age {{ x.age }}
    </li>
</ul>


</template>

<script>
export default {
    name: 'for_loop',
    data() {
        return {

            loop: ['java', 'js', 'python', 'css', 'vue js', 'node js'],
            // <!-- examople of using for loop in object array -->

            obje: [{
                    id: "0",
                    name: "suryanh",
                    age: "23",
                },
                {
                    id: "1",
                    name: "sujit",
                    age: "45",
                },
                {
                    id: "2",
                    name: "anil",
                    age: "67",
                },
                {
                    id: "3",
                    name: "rajesh",
                    age: "89",
                }

            ]

        }
        // lets create the object array

    }
}
</script>
