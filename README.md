<!DOCTYPE html>
<html>
<head lang="en">
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE-edge" />
  <meta name="viewport" content="width=devide-width, initial-scale=0.1" />
  <title>MADAM SORRY.   :)</title>
  <style>
    .image-center {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 80px;
    }
    .text-center {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 80px;
    }
    .iyaa {
      background-color: #8df19a;
      border: none;
      color: white;
      padding: 15px 32px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 17px;
      cursor: pointer;
    }
    .tricky {
      position: absolute;
      left: auto;
      right: auto;
    }
  </style>
</head>
<body>
  <div class="image-center">
    <img src="https://wallpapercave.com/wp/wp2749789.jpg" alt="image" Id="image-alt" width=700px/>
  </div>
  <div class="text-center">
    <h1 id="text">I Am Sorry jaan, please maaf kardo .......!</h1>
  </div>
  <div class="text-center">
    <button type="button" class="iyaa" > OK baby kardiya....</button>
  </div>
  <div class="tricky">
    <button type="button" class="gamau" style="background-color: red;" >NHI KARUNGI</button>
  </div>
  <script>
    let iyaa = document.querySelector(".iyaa");
    let Gamau = document.querySelector(".tricky");
    iyaa.addEventListener("click", function() {
      document.getElementById("image-alt").src = "https://gifdb.com/images/high/animated-cute-cat-sincere-thank-you-so-much-twmq95kkfsf4oirx.gif";
      
      document.getElementById("text").innerHTML = "THANKU SO MUCH MERI JAAN &hearts; &hearts; &hearts; &hearts;"
    });
    Gamau.addEventListener("mouseover", function () {
      Gamau.style.left = Math.random()*90 + "%";
      Gamau.style.top = Math.random()*90 + "%";
    });
  </script>
</bodyl>
</html>
