
<template>
  <article>
      <form>
       <div class="form-container">
         <h2 style="text-align: center;">Login</h2>
           <ul class="list">
             <li><label for="Username">Username</label></li>
             <li><input type="text" name="Username" placeholder="Username" ></li>
             <li><label for="Password">Password</label></li>
             <li><input type="password" name="Password" placeholder="Password" ></li>
             <li><input type="button" name="submit" value="Login"></li>
             <li>Don't have an account yet?<a href="#">create an account</a></li>
          </ul>
      </div>
     </form>
  </article>
</template>

<script>

export default {
  
}
</script>


<style  scoped>
  *{margin: 0; padding:0}
body{
    background-color: gainsboro;
    padding-top: 20vh;
}

.form-container{
    width:400px;
    height: auto;
    padding:20px 30px;
    background-color: #fff;
    box-shadow: 0 0 5px 0 #000;
    margin: auto;
    
}

ul.list{
    list-style-type: none;
    text-align: left;
}

ul.list li{
    width:400px;
    margin-bottom: 10px;
    border-radius: 3px;
}

ul.list li input {
    width:400px;
    text-align: center;
    padding: 8px 0px;
    border: none;
    background-color: #d3d3d3;
    border-radius: 3px;
    text-align: left;
}

ul.list li label{
    text-align: left;
}

ul.list li input[type="button"]{
    background-color: #4cc552;
    color: #fff;
    text-align: center;
}
  
</style>