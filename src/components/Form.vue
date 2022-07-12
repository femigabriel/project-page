<template>
  <div class="form">
    <form>
      <div class="title">
        <h1>Project Settings</h1>
        <p>
          Let's get started by filling the information to create your new
          project.
        </p>
      </div>
      <div class="form-input">
        <div class="form-info">
          <div class="form-label">
            <label for="">Project Name</label>
          </div>
          <div>
            <input type="text" placeholder="Project Nero" />
          </div>

          <div class="form-label">
            <label for="">Description</label>
          </div>
          <div>
            <textarea class="inputs" name=""> </textarea>
            <p>Brief descrition for your profile. URL are hyperlinked</p>
          </div>
        </div>
      </div>
      <div class="side-down">
        <div class="input">
          <h3>Add Team Member</h3>
          <div class="flex">
            <input type="text" class="text" placeholder="Email Address" />
            <button><i class="las la-plus"></i>Add</button>
          </div>
        </div>
        <div class="flex">
          <img src="../images/Dp.png" alt="" />
          <div class="content">
            <h3>Available to hire</h3>
            <p>calvin@example.com</p>
          </div>
        </div>
        <div class="flex">
          <img src="../images/profile.png" alt="" />
          <div class="content">
            <h3>Available to hire</h3>
            <p>calvin@example.com</p>
          </div>
        </div>
        <div class="flex">
          <img src="../images/profile-1.png" alt="" />
          <div class="content">
            <h3>Available to hire</h3>
            <p>calvin@example.com</p>
          </div>
        </div>
      </div>
      <Privacy />
    </form>
    <!-- <Privacy /> -->
  </div>
</template>

<script>
import Privacy from "./Privacy.vue";

export default {
  components: {
    Privacy,
  },
};
</script>

<style scoped>
.form {
  display: flex;
  align-items: center;
  justify-content: center;
  border: 3px solid whitesmoke;
  padding-top: 40px;
}
@media only screen and (max-width: 480px) {
  .form {
 
  padding-left: 25px;
}
}
.title {
  padding-bottom: 20px;
}
.form-input {
  color: #999;
  max-width: 80%;
}
.form-info {
  padding-bottom: 20px;
  /* padding-left: 5px; */
}
.flex {
  display: flex;
  padding: 20px 0px;
  /* margin-bottom: 30px; */
  border-bottom: 1px solid #e5e4e2;
}
/* .flex h3 {
margin-bottom: 20px;
} */
.text {
  width: 65%;
 
}
.input h3 {
 margin-top: 20px;
 color: #999;
}
.username {
  
  border: 2px solid #999;
  background: whitesmoke;
  padding: 5px 10px;
  border-radius: 3px;
  cursor: pointer;
  height: 40px;
  margin-bottom: 30px;
  margin-left: 10px;
}
.content {
  padding-left: 20px;
  /* padding-top: 10px; */
}
p {
  color: #999;
  font-size: 16px;
}

img {
  width: 10%;
  /* margin: 0 40px; */
}
input {
  border:2px solid #e5e4e2;
  width: 100%;
  height: 40px;
  /* border: none; */
  outline: none;
  font-size: 1.4rem;
  font-weight: 400;
  margin-bottom: 20px;
  border-radius: 5px;
}
input[type] {
  padding-left: 20px;
}
button {
  display: flex;
  background: #fff;
  padding: 0px 15px;
  border: 1px solid #e5e4e2;
  /* border: none; */
  border-radius: 5px;
  margin: 0px 10px;
  /* background: #e5e4e2; */
  height: 40px;
  align-items: center;
  font-size: 16px;
    font-weight: 700;
}
.las {
  font-size: 16px;
  color: #999;
  font-weight: 900;
 
}
label {
  font-weight: 600;
  display: inline-block;
  width: 100%;
  font-size: 1.2rem;
  margin-bottom: 15px;
}
textarea {
   border:2px solid #e5e4e2;
  width: 100%;
  height: 80px;
  border-radius: 5px;
}
</style>
