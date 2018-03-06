<template>
  <div id="app">
    <div class="row header">
        <div class="col-md-6">
          <div class="logo">
            <h1>LOGO</h1>
          </div>
        </div>
        <div class="col-md-6">
          <div class="nav-linker d-flex justify-content-end">
            <ul>
              <li><router-link to="/home">Home</router-link></li>
              <li><router-link to="/signup">SignUp</router-link></li>
              <li><router-link to="/Login">Login</router-link></li>
            </ul>
          </div>
        </div>
      </div>
    <router-view/>
    <div class="footer">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-6">
            <p>Example Program @ all rights reserved</p>
          </div>
          <div class="col-md-6 powered">
            <p>Powered By CodeJunkers</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
.header{
  display: flex;
  align-items: center;
  justify-content: center;
  border-bottom:1px solid black;
}
ul{
  list-style-type: none;
  padding: 0px;
  margin:0px;
}
li{
  float:left;
  padding:0em 1em;
}
.footer{
  border-top:1px solid red;
  border-bottom:1px solid black;
}
.footer p{
  padding:1em;
  margin:0em;
}
.powered{
  display:flex;
  align-items: center;
  justify-content: end;
}
.basic{
  display:flex;
  align-items: center;
  justify-content: center;
  height:80vh;
}
</style>
