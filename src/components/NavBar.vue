<template>
  <nav class="navbar navbar-expand-lg navbar-white bg-white">
  <div class="container">
    <div class="d-flex">
        <a class="navbar-brand" href="#">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Instagram_logo.svg/840px-Instagram_logo.svg.png" width="120" height="40" alt="">

    </a>
    <div class="dropdown-toggle mt-2"  type="button" id="dropdownMenu2" data-bs-toggle="dropdown" aria-expanded="false">

    </div>



    </div>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">

      <form class="d-flex ms-auto me-auto">
        <a href="" class="search-div">
            <i class="fa-solid fa-magnifying-glass"></i>
        </a>
        <input class="form-control search-bar" type="search" placeholder="Search" aria-label="Search">

      </form>
      <ul class="navbar-nav  mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link " aria-current="page" href="#">
            <img src="https://cdn-icons-png.flaticon.com/512/3405/3405771.png" class="nav-logo" alt="">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="https://cdn-icons-png.flaticon.com/512/1384/1384090.png" class="nav-logo" alt="">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="https://cdn-icons-png.flaticon.com/512/3161/3161837.png" class="nav-logo" alt="">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="https://cdn-icons-png.flaticon.com/512/77/77521.png" class="nav-logo" alt="">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="https://cdn-icons-png.flaticon.com/512/1077/1077035.png" class="nav-logo" alt="">
          </a>
        </li>
        <img src="https://scontent.fccu20-1.fna.fbcdn.net/v/t39.30808-6/223223926_489625255672177_237755659900963056_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=zXUmVPTeE_IAX_NrmJ7&tn=Z0jYfRH9dBmlaux6&_nc_ht=scontent.fccu20-1.fna&oh=00_AT8HK-tuSWDKPYnz3Rf-FF0hzqk63Q0gWzmv3SzryXdWMQ&oe=631DE178" class="user-profile" alt="">

      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style>
nav{
    padding: 4px 18% !important;
    border: 1px solid #DBDADA;
}
.search-bar{
    width: 265px !important;
    position: relative;
    left: 10%;
    border-radius: 6px;
    background-color: #EFEFEF;
    border: none;
    font-weight: 340 !important;
    padding-left: 38px;
}
.search-div{
    color: #8E8E8E;
    position: relative;
    left: 20%;
    top: 5px;
    z-index: 10000;
    font-weight: 300 !important;

}
.nav-link{
   color: black;
   font-size: 20px;
}
.nav-logo{
    width: 23px;
    height: 23px;
    margin-right: 11px;
}
.user-profile{
    width: 30px;
    height: 30px;
    border-radius: 50%;
    object-fit: cover;
    margin-top: 3%;
}
</style>