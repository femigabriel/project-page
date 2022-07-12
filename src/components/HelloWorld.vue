<template>
 <header class="header" id="header">
   <nav class="navbar container">
    
      <a href="./index.html" class="brand"><i class="las la-home"></i></a>
      <div class="menu" id="menu">
         <ul class="menu-inner">
            <li class="menu-item"><a class="menu-link" href="#">Project<i class="arrow left"></i></a></li>
            <li class="menu-item"><a class="menu-link" href="#">Project Nero<i class="arrow right"></i></a></li>
         </ul>
      </div>
      <!-- <form class="search-block">
         <input type="search" name="search" class="search-input" placeholder="Search here..." autofocus>
      </form> -->
   </nav>
</header>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>


main {
   overflow: hidden;
}

.las {
  font-size: 32px;
  color: #333;
  margin: 0 30px;
  /* opacity: 0.5; */
}
.container {
   /* max-width: 75rem; */
   height: auto;
   margin: 0 auto;
   padding: 0 1.25rem;
}

.brand {
   font-size: 1.5rem;
   font-weight: 600;
   line-height: 1.5;
    margin: 0 10px;
}
.header {
   background-color: #ffff;
   /* border-bottom: 2px solid whitesmoke; */

}

.navbar {
   display: flex;
   flex-direction: row;
   align-items: center;
   height: 4rem;
   margin: 0 auto;
   
}
@media only screen and (max-width: 480px) {
  .navbar {
     display: none;
      
  }
  /* .menu-link {
    margin: 10px 30px;
  } */
}
.menu {
 transition: all 0.45s ease-in-out;

   }

ul {
  list-style-type: none;
  padding: 0;
  font-size: 16px;
   


}
@media only screen and (max-width: 480px) {
  ul {
    display: none;
  }
  .menu {
 transition: all 0.45s ease-in-out;

   }
}
li {
   border-right: none;
     display: flex;
        margin: 0 40px;
}
li {
  /* border-right: solid 3px darkgrey; */
  display: inline-block;
  margin: 0 40px;
  padding-right: 10px;
  transition: all 0.45s ease-in-out;
}
a {
  color: #333;;
}
</style>
