<template>
  <div class="hello">
    <h2>User Registration Portal</h2>
    <h4>{{ msg }}</h4>
    <div>
      <br/>
      <br/>
      <p><b>Click <a href="/register" target="_blank"><u>here</u></a> to register yourself</b></p>
      <br/>
      <br/>
      
    </div>
  </div>
</template>

<script>
    export default {
        name: 'Index',
        data () {
            return {
                
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

  a {
    color: #3222b9;
  }
</style>
