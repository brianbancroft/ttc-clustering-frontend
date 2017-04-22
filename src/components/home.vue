<template>
  <div>
    <header>
      Header
    </header>
    <main>
      <h1>Main Page</h1>
      <home-page></home-page>
    </main>
    <footer>
      Body
    </footer>
  </div>

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
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
