<template>
  <div>
    <div class="container-fluid">
      <div class="body">
        <div class="row">
          <div class="col-md-12">
            <h2>WELCOME TO THE HOME PAGE IN HOME.VUE</h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to the Home'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*div{
  border:1px solid black;
}*/
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
  /*float:right;*/
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.body{
  height:80vh;
  display:flex;
  align-items: center;
  justify-content: center;
}
/*.logo {
  float:right;
}*/
</style>
