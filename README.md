<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="robots" content="noindex">
    <link rel="stylesheet" href="pp.css">
    <title>Popup Example</title>
</head>
<body>
  <div class="btn" onclick="ishu()">Login</div>
  <div class="k">
    <p class="happy">Happy</p>
    <h1 class="velen">Velentine day</h1>
  </div>
  <div class="k1">
     <h4 class="t1">vaibhav</h4>
    <nav class="p1">
      <img src="1.png">
    </nav>
    
  </div>
  <div class="k2">
     <h4 class="t2">vaibhav</h4>
    <nav class="p2">
      <img src="2.png">
    </nav>
  </div>
  <div class="k3">
    <h4 class="t3">vaibhav</h4>
    <nav class="p3">
      <img src="3.png">
    </nav>
  </div>
  <div class="k4">
     <h4 class="t4">vaibhav</h4>
    <nav class="p4">
      <img src="4.png">
    </nav>
  </div>
  <div class="k5">
    <h4 class="t5">vaibhav</h4>
    <nav class="p5">
      <img src="5.png">
    </nav>
  </div>
  <div class="scren" id="tisha">
    <div class="b">
      <span onclick="pp()" class="x">&times;</span>
      <h4>Enter your login ID</h4>
      <hr>
      <form onsubmit="return false;">
        <p class="naam">User ID</p>
        <input class="a" type="text" id="user"><br>
        <p class="pass">Password</p><br>
        <input class="c" type="password" id="psd"><br><br>
        <button type="button" onclick="sp()" class="e"><a href="sub.html">Submit</a></button>
      </form>
      <p id="j" class="p"></p>
      <p class="sin">Sing-up to contact Vaibhav</p>
    </div>
  </div>
  
  <script>
  
        function ishu(){
          var x = document.getElementById("tisha")
          x.style.display = 'block';        
        } 
  
       function pp(){
          var x = document.getElementById("tisha")
          x.style.display = 'none';        
        }   
  
  
     function sp(){
       event.preventDefault();
       var x = document.getElementById("user").value;
       var y = document.getElementById("psd").value;
       var z = x=="Vaibhav" && y=="ishu" ? " USER FOUND" : "USER NOT FOUND";
       document.getElementById("j").innerHTML = z
       
       
       if (z == " USER FOUND") {
          window.location.href = "sub.html";
    }
       
     }
       
       
  </script>
</body>
</html>
