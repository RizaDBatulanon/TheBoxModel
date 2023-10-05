<!DOCTYPE html>
<html>
<head>
  <title>Cat</title>
  <style>
    .box {
      width: 200px;
      height: 200px;
      border: 2px solid black;
      padding: 50px;
      margin: 30px;
      margin: 0 auto;
      position: relative;
    }

    .box img {
      display: block;
      margin: 0 auto;
      max-width: 100%;
      max-height: 75%;
      border-radius: 50%;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

    .box h6 {
      text-align: center;
      position: absolute;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
    }
  </style>
</head>
<body>
  <div class="box">
    <img src="https://images.pexels.com/photos/14440674/pexels-photo-14440674.jpeg"
  >

    <h6>I am a Cat</h6>
  </div>
</body>
</html>
