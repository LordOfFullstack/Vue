<template>
  <div class="hello">
    <h1>{{ warning }}</h1>
  </div>
</template>

<script>
export default {
  name: 'footer',
  data () {
    return {
      warning: 'this is footer'
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
