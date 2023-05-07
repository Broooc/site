<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="apple-touch-icon" sizes="72x72" href="favicons/apple-touch-icon.png">
        <link rel="icon" type="image/png" sizes="32x32" href="favicons/favicon-32x32.png">
        <link rel="icon" type="image/png" sizes="16x16" href="favicons/favicon-16x16.png">
        <link rel="manifest" href="favicons/site.webmanifest">
        <link rel="mask-icon" href="favicons/safari-pinned-tab.svg" color="#0dc6ff">
        <meta name="msapplication-TileColor" content="#da532c">
        <meta name="theme-color" content="#ffffff">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" crossorigin="anonymous"></script>
        <meta charset="UTF-8">
        <title>Hobbies</title>
        <style>
            .b{
                background: Pink;
            }
            .card {
                border-radius: 1em;
                text-align: center;
            }
            .card:hover {
                background-color: rgba(0, 0, 0, 0.2);
            }
            .card img {
                border-radius: 4%;
            }
        </style>
    </head>
    <body class="b">
    <nav class="navbar navbar-expand-lg bg-white">
  <div class="container">
   <a class="navbar-brand" href="#">
     <img src="In.png" height="60" alt="logotype">
   </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="start.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#">Hobbies</a>
        </li>
      </ul>
    </div>
  </div>
  </nav>
    <div class="container my-5">
        <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3">
            <a class="btn" href="https://youtu.be/izGwDsrQ1eQ" target="_blank">
                <div class="col">
                <div class="card">
                    <img src="saxaphone.jpg" class="card-img-top" alt="Sax">
                    <div class="card-body">
                        <h5 class="card-title">Saxophone</h5>
                        <p class="card-text">I'm playing saxophone over 7 years, and its don't get boring.</p>
                    </div>
                </div>
            </div>
            </a>
            <a class="btn" href="https://en.wikipedia.org/wiki/Programming_language" target="_blank">
                <div class="col">
                <div class="card">
                    <img src="Python.svg.png" class="card-img-top" alt="Petuhon">
                    <div class="card-body">
                        <h5 class="card-title">Programming</h5>
                        <p class="card-text">This site is my first website ever! </p>
                    </div>
                </div>
            </div>
            </a>
        </div>
    </div>
    </body>
</html>
