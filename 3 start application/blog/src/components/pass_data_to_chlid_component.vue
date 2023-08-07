<!-- parents file -->

<template>
<h1>--------------------------------------------------</h1>

<child name="suryansh pundir " />
<child post="khudana" />
<child getdata="getdata" />
</template>

<script>
import child from './child.vue';
export default {
    name: 'pass_data_to_chlid_component',
    components: {
        child,
    },
        methods: {
            getdata() {
                console.warn("i coming from parents to child home guys")
            }

        }
    
}
</script>
