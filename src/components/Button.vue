<template>
<div id="btn">
     <a href="#">
         <i class="fas fa-address-book"></i>
         <span>{{caption}}</span>
      
     </a> 
</div>
 
</template>

<script>
export default {
    name:'Button',
    props:[
        'caption'
    ]
}
</script>

<style lang="scss" scoped>
#btn {
    border: 1px solid black;
    position:relative;
    width:fit-content;
    height:fit-content;
    border-radius: 5px; 
     padding: 5px; 
     background-color: aquamarine;
    a {
       
        display:flex;
         text-decoration: none;
    }
}
</style>