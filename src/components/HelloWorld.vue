<template>
  <div>
    <h1>webcomponent test</h1>
    <div id="comout">
      <div class="out-title">
        out title
      </div>
    </div>
    <div id="comin">
      <template id="comtemp">
        <div class="temp-title">
          temp title
        </div>
        <div class="out-title">
          temp test for out title
        </div>
        <div class="in-title">
          temp test for in title
        </div>
      </template>
      <div class="in-title">
        in title
      </div>
    </div>
  </div>
</template>

<script>



export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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
