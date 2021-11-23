<template>  
    <h1>{{ msg }}</h1>
</template>

<script>
export default {
   name: 'MyFirstApp',
   props: {
       msg: String
   }
        
    
}
</script>

<style>
h1 {
    font-size: 38px;
    color: blueviolet;
    font-style: italic;
}

</style>
