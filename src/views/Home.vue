<template>
  <div class="home">
    <div class="wrap">
      <div class="menu">
        <li><img src="../assets/img/btn-02.png" alt=""></li>
        <li><img src="../assets/img/btn-03.png" alt=""></li>
        <li><img src="../assets/img/btn-04.png" alt=""></li>
        <li><img src="../assets/img/btn-05.png" alt=""></li>
        <li><img src="../assets/img/btn-06.png" alt=""></li>
        <li><img src="../assets/img/btn-07.png" alt=""></li>
      </div>
    </div>
    <div class="content">
      <div class="kv"></div>
      <div class="kv"></div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  }
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
}

.wrap{
   position: fixed;
   margin:auto;
   left:0;
   right:0;
   top:0;
   bottom:0;
   z-index: 999;
}

.menu{
  margin-top: 20px;
}

.wrap li{
  display: inline-block;
  margin-left: 0.1%;
  margin-right: 0.1%;
}

.content {
  position: relative;
  width: 769px;
  height: 875px;
  margin: 0 auto;
  padding: 0;
}

.content .kv{
  background-image: url(../assets/img/kv_main-02.png);
  /* background-size:769px 875px; */
  position: relative;
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
  /* min-height: 130.20833vw; */
  background-position: center 0;
  background-repeat: no-repeat;
}

</style>