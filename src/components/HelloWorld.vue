<template>
<!-- header -->
<div class="header-area">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <div class="top-header-content d-flex align-items-center justify-content-between">
          <div class="logo">
            <div href="#" id="app">
              <img src="">
            </div>
          </div>
          <div class="d-flex">
            <div class="d-flex">
              <ul class="nav-item"><a href="#" class="become-author-area nav-item">Become an author</a></ul>
              <button type="button" class="btn btn-primary loginuser">Login</button>
            </div>
          </div>
        </div> 
      </div>
    </div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="collapse navbar-collapse" id="navbarText">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Sektor </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Panduan pelaksanaan</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Publikasi</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Pendanaan </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Regulasi </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Topik</a>
      </li>
    </ul>
  </div>
        <form class="form-inline">
        <input class="form-control mr-sm-2" type="search" placeholder="Search document" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
    </nav>
  </div>
  <div class="container">
    <div class="row">
    <div class="col-8">
      <h1 class="artikel-populer"> ARTIKEL POPULER </h1>
      <div class="jumbotron jumbotron-fluid">
        <div class="container">
          <h1 class="display-4">IMAGE</h1>
          <p class="judul"> Judul artikerl</p>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <div class="jumbotron jumbotron-fluid">
            <p class="judul"> Judul artikerl</p>
          </div>
        </div>
        <div class="col">
          <div class="jumbotron jumbotron-fluid">
            <p class="judul"> Judul artikerl</p>
          </div>
        </div>
      </div>
    </div>
    <div class="col-4">
      <h1 class="artikel-populer"> DOKUMEN POPULER </h1>
      <div>
      </div>
    </div>
  </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
.top-header-content {
    width: 100%;
    height: 100px;
    background-color:white;
    position: relative;
    z-index: 1;
}
.d-flex{
    padding: 10px 10px;

}
.become-author-area{
    display: inline-block;
    padding: 10px 40px 10px 10px;
    color: blue;
}
.loginuser{
  height: 35px;	
  width: 92px;
}
.artikel-populer {	
  height: 32px;	
  width: 228px;	
  color: #172B4D;	
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;	
  font-size: 20px;	
  line-height: 32px;
  margin: 10px 0px;
}
.judul{
  float: left;
  padding: 10px;
}
</style>
