<template>
  <div id="app">
    <!-- navbar -->
    <nav class="shadow-sm p-3 mb-5 bg-white rounded navbar navbar-expand-lg navbar-light bg-light">
      <div class>
        <a class="navbar-brand" href="#">
          <div class="navbnd">AdviceByte</div>
        </a>
      </div>
      <div class="spacenav">
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link active" href="#">
              Menu 0
              <span class="sr-only">(current)</span>
            </a>
            <a class="nav-link" href="#">Menu 1</a>
            <!-- <a class="nav-link" href="#">Menu 2</a> -->
            <!-- <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Menu 3</a> -->
          </div>
        </div>
      </div>
    </nav>
    <!-- content -->
    <div class="container-fluid">
      <div class="container">
        <div class="my_div"></div>
        <button class="btn btn-primary">This is test primary</button>
        <button class="btn btn-danger">This is test danger</button>
      </div>
      <div class="row">
        <!-- first col -->
        <div class="col-md-3">One of three columns</div>
        <!-- sec (Center) col -->
        <div class="col-md-6">
          <div class="container">One of three columns</div>
        </div>
        <!-- third col -->
        <div class="col-md-3">
          <!-- ranking card list -->
          <div class="card" style="width: 18rem;">
            <div class="card-header">
              <p class="cardhd">Weekly Ranking</p>
            </div>
            <!-- ลำดับรายชื่อ Ranking -->
            <ul class="list-group list-group-flush">
              <!-- <div class="row"> -->
              <li class="list-group-item-light">
                <div class="text-rank-format-1">One of Ranking</div>
                <!-- </div>   -->
              </li>
              <li class="list-group-item-light">
                <div class="text-rank-format-1">One of Ranking</div>
                <!-- </div>   -->
              </li>
              <li class="list-group-item-light">
                <div class="text-rank-format-1">One of Ranking</div>
                <!-- </div>   -->
              </li>
              <li class="list-group-item-light">
                <div class="text-rank-format-1">One of Ranking</div>
                <!-- </div>   -->
              </li>
              <li class="list-group-item-light border-custom">
                <a href="#" class="seemore">Show more</a>
              </li>
            </ul>
          </div>
          <div class="boxspace-card"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
.navbnd {
  /* logo advicebyte font */
  font-weight: bold;
  color: #0c4377;
  /* padding: 10%; */
  margin-left: 20%;
  margin-right: 5%;
}
.spacenav {
  /* ระยะ margin padding ห่างระหว่างโลโก้กับเมนู */
  margin-left: 30px;
  /* margin-right: 20%; */
}
.cardhd {
  float: left;
  font-weight: bold;
  font-size: 18px;
  color: white;
}
#card-header {
  border-radius: 100px;
}
/* ------------------------------------------------------- */
html {
  height: 200%;
}
#app {
  color: #2c3e50;
  max-width: 400%;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}
.slide-fade-enter-active {
  transition: all 0.2s ease;
}
.slide-fade-leave-active {
  transition: all 0.2s cubic-bezier(1, 0.5, 0.8, 1);
}
.slide-fade-enter,
.slide-fade-leave-active {
  padding-left: 10px;
  opacity: 0;
}
</style>
