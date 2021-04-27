<template>
    <h1>{{title}}</h1>
    <Simple />
</template>

<script>
import Simple from './components/Simple'
export default {
    name: 'App',
    data() {
        return {
            title: 'My Vue App'
        }
    }
    components: {
        name: 'Simple'
    }
}
</script>


<style scoped>

</style>

