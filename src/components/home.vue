<template lang="pug">
  .div
    header
    |  Header
    
    main
      h1 Main Page
    |  home-page

    footer
    |  Footer
</template>

<script>
import HomePage from './HomePage.vue'
export default {
  name: 'hello',
  components: {
    'home-page': HomePage
  },
  data () {
    return {
      msg: 'App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="sass">
h1, h2 
  font-weight: normal


ul
  list-style-type: none
  padding: 0


li
  display: inline-block
  margin: 0 10px


a
  color: #42b983

</style>
