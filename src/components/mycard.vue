<template>
  
  <!-- <div class="card">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZYDmYNyRzoZheVVmDPUWynWSVrjmftv8wfg&s" alt="Avatar" style="width:50%">
  <div class="container">
    <h4><b>John Doe</b></h4> 
    <p>Architect & Engineer</p> 
  </div>
    <img :src="image" alt="name" style="width: 100%;">
    <div class="container">
      <h4><b>{{ name }}</b></h4>
      <p>{{ ninkname }}</p>
      <p>{{ tel }}</p>
      <p>{{ email }}</p>
    </div>
</div> -->

<div class="card">
  <!-- <img src="/w3images/team2.jpg" alt="John" style="width:100%"> -->
  <img :src="image" alt="name" width="280px" height="200px" >
  <!-- <h1>John Doe</h1>
  <p class="title">CEO & Founder, Example</p>
  <p>Harvard University</p> -->
  <div class="container">
      <h1><b>{{ name }}</b></h1>
      <p>{{ id }}</p>
      <p>{{ tel }}</p>
      <p>{{ email }}</p>
  </div>
  <div style="margin: 24px 0;">
    <a href="#"><i class="fa fa-dribbble"></i></a> 
    <a href="#"><i class="fa fa-twitter"></i></a>  
    <a href="#"><i class="fa fa-linkedin"></i></a>  
    <a href="#"><i class="fa fa-facebook"></i></a> 
  </div>
  <p><button>Contact</button></p>
</div>

</template>

<script>
export default {
  props: ["id", "name", "nickname", "tel", "email", "image"]
}
</script>

<style scoped>
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 500px;
  text-align: center;
  font-family: arial;
  display: inline-block; 
  margin-left: 10%;
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 10px;
  margin: 10px;
  width: 300px;
  margin-left: 10%;
  background-color: aliceblue;
}

.price {
  color: grey;
  font-size: 22px;
}

.card button {
  border: none;
  outline: 0;
  padding: 12px;
  color: white;
  background-color: #5f211d;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

.card button:hover {
  opacity: 0.7;
}

/* img {
  max-width: 500px;
  max-height: 400px;
} */

</style>