
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mister Graph Studio</title>

  <style>
    body{
      margin:0;
      font-family:Arial;
      background:#111;
      color:white;
      text-align:center;
    }

    header{
      padding:60px 20px;
    }

    h1{
      font-size:40px;
    }

    p{
      color:#ccc;
    }

    .btn{
      display:inline-block;
      margin-top:20px;
      padding:12px 25px;
      background:white;
      color:black;
      text-decoration:none;
      border-radius:8px;
      font-weight:bold;
    }

    .gallery{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
      gap:10px;
      padding:20px;
    }

    .gallery img{
      width:100%;
      border-radius:10px;
    }
  </style>
</head>

<body>

<header>
  <h1>Mister Graph Studio</h1>
  <p>Photographe & Vidéaste</p>

  <a class="btn" href="https://instagram.com">
    Mon Instagram
  </a>
</header>

<section class="gallery">
  <img src="https://picsum.photos/400/500?1">
  <img src="https://picsum.photos/400/500?2">
  <img src="https://picsum.photos/400/500?3">
</section>

</body>
</html>
