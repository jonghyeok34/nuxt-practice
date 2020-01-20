<template>
  <div>
  <Nav/>
    <nuxt />
  </div>
</template>

<script>
import Nav from './partials/nav';

export default {
  components:{
    Nav
  }  
}
</script>
<style>
    header {
        background: rgb(0, 219, 146);
        display: grid;
        grid-template-columns: repeat(2,auto);
    }
    .logo, li a {
        padding: 1em 2em;
        display: block;
        text-transform: uppercase;
        text-decoration: none;
        font-weight: bold;
        color: white;
        font-size: .9em;
    }
    nav {
        justify-self: right;
    }
    ul {
        list-style-type: none;
    }
    li {
        display: inline;
    }
    li a {
        padding: 1em 2em;
        display: inline-block;
        background: rgba(0,0,0,0.1);
    }
</style>
