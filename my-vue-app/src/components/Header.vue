<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent',
    props: {
        title:{
            type: String,
            required: true
        }
    }

};
</script>

<style scoped>
header {
    background-color: #42b983;
    color: white;
    padding: 15px;
    text-align: center;
}
</style>