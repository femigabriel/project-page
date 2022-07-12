<template>
  <div class="side-bar">
    <div class="search">
      <i id="search" class="las la-search"></i>
      <div class="search-input">
        <input type="text" placeholder="Search" />
      </div>
    </div>
    <div class="profile">
      <i class="lar la-bell"></i>
      <img src="../images/Dp.png" alt="profile" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.side-bar {
  float: right;
  justify-content: space-between; 
  display: flex;
  margin: -30px 60px;
}
input {
  background: #87CEFA;
  color: #fff;
  width: 100%;
  font-size: 22px;
  border: none;
  outline: none;
  border-radius: 5px;
  height: 30px;
  /*  */
}
@media only screen and (max-width: 480px) {
input {
  background: #87CEFA;
  color: #fff;
  width: 60%;
  font-size: 22px;
  border: none;
  outline: none;
  border-radius: 5px;
 margin: 0px 60px;
}
.side-bar {
  display: flex;
  margin: -30px 20px;
}
.lar {
  margin: 5px 120px;
  display: none;
}
.profile {

  /* margin-left: 20px; */
}
}
.search {
  margin-right: -40px;
}

input::placeholder {
  color: #fff;
  padding-left: 30px;
  font-size: 15px;
  opacity: 0.5;
}
.las {
  font-size: 18px;
  color: #fff;
  position: relative;
  left: 25px;
  top: 6px;
  opacity: 0.5;
}
.search {
  display: flex;
}
.profile {
  display: flex;
  padding: ;
}

.lar {
  font-size: 22px;
  color: whitesmoke;
  margin: 5px 60px;
  /* opacity: 0.5; */
}
.profile img {
  width: 35px;
   margin: 0 0px;
}
</style>
