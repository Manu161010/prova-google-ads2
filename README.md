# prova-google-ads2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sito di Prova</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .navbar {
            background-color: #333;
            overflow: hidden;
        }
        .navbar a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .image-section {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }
        .image-section img {
            max-width: 30%;
            height: auto;
        }
    </style>
 <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-16641954077">
</script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'AW-16641954077');
</script>

</head>
<body>
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </div>
    
    <div class="container">
        <h1>Benvenuto al Sito di Prova</h1>
        <p>Questo è un sito di prova creato per testare le campagne Google Ads.</p>
        
        <div class="image-section">
            <img src="https://via.placeholder.com/300" alt="Placeholder Image 1">
            <img src="https://via.placeholder.com/300" alt="Placeholder Image 2">
            <img src="https://via.placeholder.com/300" alt="Placeholder Image 3">
        </div>
    </div>

    <div class="footer">
        <p>Footer del Sito di Prova</p>
    </div>
</body>
</html>
