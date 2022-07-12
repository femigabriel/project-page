<template>
  <div class="hello">
    <header>
      <div class="header">
        <div class="logo">
          <!-- <img src="../images/logo.png" alt=""> -->
          <h3>Logo</h3>
        </div>
        <ul>
          <li><span>Dashboard</span></li>
          <li>Jobs</li>
          <li>Applicants</li>
          <li>Company</li>
        </ul>
        <div class="icon">
           <i class="las la-bars"></i>
      </div>
     
      </div>
       
      <SearchInput />
     
    </header>
  </div>
</template>

<script>
import SearchInput from "./SearchInput.vue";
export default {
  name: "HelloWorld",
  components: {
    SearchInput,
  },
  props: {
    msg: String,
  },
};
</script>

<style scoped>
header {
  padding-top: 10px;
  padding-bottom: 10px;
  background: #00bfff;
}
.logo {
  display: flex;
  margin: 0 40px;
}
.logo img {
  margin: 0 30px;
  /* width: 20px; */
}
header h3 {
  font-size: 20px;
  margin: 20 40px;
  color: greenyellow;
}
header h1 {
  color: #fff;
  margin-left: 40px;
  margin-top: 40px;
}
.header {
  display: flex;
  margin: 0 10px;
}
ul {
  list-style-type: none;
  color: #fff;
  font-size: 16px;
}
li {
  display: inline-block;
  margin: 5px 40px;
}
span {
  /* background: #0b4657; */
  padding: 5px 5px;
  border-radius: 5px;
}
.icon {
  display: none;
  font-size: 25px;
}
@media only screen and (max-width: 768px) {
  .logo {
  margin: 0 10px;
}
  
  /* .icon {
    
  font-size: 50px;
  color: red;
} */
li {
  display: none;
  ;
}
}


</style>
