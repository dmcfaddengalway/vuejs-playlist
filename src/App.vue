<template>
    <div>
        <h1>{{ title }}</h1>
        <ninjas></ninjas>
    </div>
</template>

<script>
    import Ninjas from './ninja.vue'
    export default {
        components: {
            'ninjas': Ninjas
        },
        data () {
            return {
                title: "Ninja App"
            }
        }
    }
</script>

<style>

</style>
