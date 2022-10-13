<template>
    
    

    <div>
        <slot></slot> 
                <p class="text-center"> {{ nombre }} </p>
                <p class="text-center"> {{ descripsion }} </p>
                <p class="text-center"> {{ precio }} </p>
                <a href="https://www.facebook.com/" target="_blank">Pedir</a>
    </div>
    
  
</template>   




<style scoped>
   
    
    div{
        width: 300px;
        
        display: inline-block; 
        text-align: center;
       
        border-radius: 1px;
        margin: 2%;
        padding: 1%;
      

    }
   
    
   
</style>

<script>

    export default {
        props: {
        
            nombre: {
                String,
            },
            descripsion: {
                String,
            },
            precio: {
                String,
            },
        },


    };
</script>

