<template>
    <div class="l-container">
        hello
    </div>
</template>

<script>
    import {LightProbeGenerator} from 'three/examples/jsm/lights/LightProbeGenerator'
    export default {
        mounted() {
            console.log(LightProbeGenerator);
        }
    }
</script>
