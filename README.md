```
<!DOCTYPE html>
<html>
<head>
  <title>Te amo Camila</title>
  <style>
    body {
      background-color: #f2f2f2;
      font-family: Arial, sans-serif;
    }
    .corazon {
      position: relative;
      width: 200px;
      height: 200px;
      background-color: #ff69b4;
      border-radius: 50%;
      transform: rotate(45deg);
    }
    .corazon::before {
      content: "";
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) rotate(45deg);
      width: 100px;
      height: 100px;
      background-color: #fff;
      border-radius: 50%;
    }
    .texto {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) rotate(-45deg);
      font-size: 24px;
      font-weight: bold;
      color: #fff;
    }
  </style>
</head>
<body>
  <div class="corazon">
    <div class="texto">Te amo Camila</div>
  </div>
</body>
</html>
```
