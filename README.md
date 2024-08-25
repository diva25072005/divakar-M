<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>Login page</title>
  <style>
  h1{
    text-align:center;
    color:yellow;
    display:block;
    
  }
  body{
    background-image:url('https://i.pinimg.com/736x/1a/2e/17/1a2e17461726554b3c0e699eac87f13d.jpg');
    background-size:cover;
 background-repeat:no-repeat;
    
  }
nav{
  display:flex;
  font-size:1px;
  border:1px solid  #FFFFFF;
  background-color:light blue;
  background:transparent;
  backdrop-filter:blur(1px);
  margin-top:0px;
  
}
nav li{
  display:inline-block;
  margin:0px 10px;
  carser:pointer;   
  }
 ul{ 
   display:;
 }
nav a{
  text-decoration:none;
  color:white;
  font-size:15px;
  
}
nav a:hover{
  color:white;}
.menu-line{
  height:2px;
  width:20px;
  background-color:black;
  margin-bottom:3px;
  margin-top:2px;
  
}
.menu{
    cursor:pointer;
  display:block;
  position:absolute;
  right:20%;
  left:90%;
  
  
}
 .login{
   margin-left:2%;
   margin-right:10px;
   margin-top:40px;
   padding:0px 0px 10px 80px;
   background:transparent;
  backdrop-filter:blur(10px);
   border:1px solid green;
   border-radius:30px;
   
 }
.new input{
   border-radius:10px;
   margin-bottom:5px;
   border:1px solid gray;  
 }
.hi input{
  width:30px;
  height:30px;
  outline:none;
  font-size:20px;
  border:1px solid green;
  
}
  
 button{
   color:blue;
   background-color:#48D1CC;
   border:1px solid gray;
   
 } 
 .box1 i{
   width:10px;
   height:30px;
  
 }
  .box1 input:hover{
    border:5px solid blue;}
  </style>
</head>
<body >
  <h1>
    welcome
  </h1>
  <nav>
    <ul>
    <li><a href="">Home</a></li>
     <li><a href="">login</a></li>
     <li><a href=""> contact </a></li>
     <li><a href="">about</a></li>
    </ul> 
    <div class="menu">
      <div class="menu-line"></div>
      <div class="menu-line"></div>
      <div class="menu-line"></div>
      <div class="menu-line"></div>
      
    </div>
  </nav>
  <form class="login">
 
  <h3>sign up to your account </h3>
    <div class="new">
      <div class="box1"> <label for="name"></label>
    <input type="text" id="name" placeholder="user name                             &#128100;" >
      <i class=""></i></div>
      <div class="box2"> 
        <label for="password"></label>
      
    <input type="password" id="password" placeholder="password                               &#128272;">
      
    <label for="confirm password"></label>
    <input type="password" id="confirm password" placeholder="confirm password                &#128273;"><br>
   <label for="mobile number"></label>
    <input type="number" id="mobile number" placeholder="mobile number                     &#128222;" maxlength="10px">
      <button type="send">send OTP</button>
      <div class="hi">
        <label for="otp">
    <input type="text" id="otp" maxlength="1px">
     <input type="text" id="otp"  maxlength="1px">
     <input type="text" id="otp"  maxlength="1px">
      <input type="text" id="otp"  maxlength="1px"> </label>
        
      </div>
      </div>  
  <label for="male">male</label>
  <input type="radio" id="male" name="gender">
  <label for="female">female</label>
  <input type="radio" id="female" name="gender"><br>
      <button type="submit">submit</button>
      <a href="">forgot password?</a>
    
    
    
  </form>
</body>
</html>

