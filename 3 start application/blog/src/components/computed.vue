<!-- computed element is used to perform higher calulatioin -->
<template>
<div>
    <h1>computed </h1>
    <br>
    from data() function {{dollar*10 + rupees}} <br>
    from computed method {{ getresult }}

</div>
</template>

<script>
export default {
    name: 'comp-uted',
    data() {
        return {
            dollar: "100",
            rupees: "500",
            pond: "9000",
        }
    },
    computed: {
        getresult() {

            return this.dollar * 10 + this.rupees+5

        }
    }
}
</script>
