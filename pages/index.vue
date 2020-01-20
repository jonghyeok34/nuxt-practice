<template>
  <div class="container">
    <h1>The Best Nuxt</h1>
    <p class="subheading">We've got the best nuxt's</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates sed tenetur quas! Laudantium odio consectetur, quia dolore veritatis quae quam nobis aperiam saepe, modi quibusdam facere tenetur omnis earum molestiae.</p>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  head(){
        return {
            title: 'Nuxt Home',
            meta:[
                {name: 'description', content:'This is my about description here.'},
                {name: 'keywords', content:'about nuxt, nuxt info'},
            ]
        }
    }
}
</script>

<style>


.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
