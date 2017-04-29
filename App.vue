<template style="">
  <div id="app" class="bg">
    <div id="">
      <nav class="navbar navbar-inverse">
          <div class="container-fluid">
            <a class="navbar-brand" href="#">
              <img src="./assets/rotten.png" class="logo" alt="">
            </a>
            <div class="navbar-header navbar-right">
              <ul class="nav navbar-nav ">
                    <li><a href="#"><span class="glyphicon glyphicon-user" aria-hidden="true"></span></a></li>
              </ul>
            </div>
          </div>
      </nav>
      <div class="col-md-12">
        <div class="panel panel-default">
          <div class="panel-heading">MOVIE</div>
            <div class="panel-body">
              Panel content
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'app'

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/

}
body {
  background-color:rgba(0, 0, 0, 0.5);
  background-image: url("image/rotten.png");
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
}
.logo{
  /*width: 10vw;*/
  height: 2vw;
}
</style>
