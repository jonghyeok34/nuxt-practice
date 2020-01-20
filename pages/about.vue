<template>
    <div class="container">
    <h1>About our nuxt</h1>
    <p class="subheading">They're juicy and stuff.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates sed tenetur quas! Laudantium odio consectetur, quia dolore veritatis quae quam nobis aperiam saepe, modi quibusdam facere tenetur omnis earum molestiae.</p>
  </div>
</template>

<script>
export default {
    transition:'bounce',
    head(){
        return {
            title: 'About Nuxt',
            meta:[
                {name: 'description', content:'This is my about description here.'},
                {name: 'keywords', content:'about nuxt, nuxt info'},
            ]
        }
    }
}
</script>
<style>

</style>