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

    a {
            border: 0;
            border-radius: 0.25rem;
            background: #1E88E5;
            color: white;
            font-family: system-ui, sans-serif;
            font-size: 1rem;
            line-height: 1.2;
            white-space: nowrap;
            text-decoration: none;
            padding: 0.25rem 0.5rem;
            margin: 0.25rem;
            cursor: pointer;
}
    }

</style>