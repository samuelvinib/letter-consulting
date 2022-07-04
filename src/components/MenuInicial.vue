<template>
  <header class="navbar">
    <div class="container grid-xl col-mx-auto">
      <div class="columns container-menu">
        <a href="index.html"><img src="../assets/media/logo.png" alt="logo"></a>
        <ul class="columns nav-container">
          <li><a href="#">HOME</a></li>
          <li><a href="#">SERVIÇOS</a></li>
          <li><a href="#">SOBRE A LETTER</a></li>
          <li><a href="#">LETTER NEWS</a></li>
          <li><a href="#">CONTATO</a></li>
        </ul>
        <div>
          <div class="columns container-search">
            <!-- <div class="search">
              <input type="text">
              <i class="icon icon-search"></i>
            </div> -->
              <ul class="icones-social-media columns">
                <li><a href="#"><img src="../assets/icons/instagram.svg" alt="icone do instagram"></a></li>
                <li><a href="#"><img src="../assets/icons/facebook.svg" alt="icone do facebook"></a></li>
                <li><a href="#"><img src="../assets/icons/linkedin.svg" alt="icone do linkedin"></a></li>
              </ul>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'MenuInicial',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container-menu{
  align-items: center;
  justify-content: space-around;
}
.navbar {
  background-color: #252A36;
  padding: 25px 0;
}
.nav-container li{
  margin: 0 8px;
}
.nav-container li:hover{
  border-top: #bc8c3d;
}
li{
  font-size: 12px;
  list-style: none;
  font-weight: bold;
}
li a{
  text-decoration: none;
  color: #FFFFFF87;
}
img{
  width: 240px;
  height: 50px;
}
.search{
  padding: 10px 0;
  border-bottom: #393d47 1px solid;
  margin-right: 40px;
}
.container-search{
  align-items: center;
}
.search input{
  background-color: #0000;
  border: none;
  color:#bc8c3d;
  font-weight: bold;
}
.search input:focus{
  border: 0 none;
  box-shadow: 0 0 0 0;
  outline: 0;
}
.icones-social-media li{
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #bc8c3d;
  width: 30px;
  height: 30px;
  margin: 0 2px;
}
.icones-social-media img {
  width: 15px;
  height: 15px;
}
</style>
