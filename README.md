<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>yasmine</title>
  <link rel="icon" type="image/x-icon" href="yasmine.jpg">
  <style>
    
    .panda-container {
  display: flex;
  justify-content: flex-end;
  margin-top: 20px;
  position: fixed;
  bottom: 0;
  right: 0;
  padding: 10px;
  z-index: 1000;
}

.animated-panda {
  width: 150px;
  animation: float 3s ease-in-out infinite;
}

@keyframes float {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-15px);
  }
}

    
    
    body {
      font-family: Ahinds, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1em;
      text-align: center;
    }
    header img {
      width: 60px;
      vertical-align: middle;
    }
    header h1 {
      display: inline;
      margin-left: 10px;
      font-size: 2em;
    }
    nav {
      background-color: #444;
      overflow: hidden;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #ddd;
      color: black;
    }
    section {
      padding: 2em;
    }
    .panda-img {
      width: 100%;
      max-width: 400px;
      display: block;
      margin-top: 1em;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1em;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    .panda-container {
  display: flex;
  justify-content: flex-end;
  margin-top: 20px;
}

.animated-panda {
  width: 200px;
  animation: float 3s ease-in-out infinite;
}

@keyframes  {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-15px);
  }
}

  </style>
</head>
<body>

  <header>
    <img src="mas.jpg" alt="Site Logo">
    <h1>Yasmine T. Caballes</h1>
  </header>

  <nav>
    <a href="#facebook">facebook</a>
    <a href="#MUSIC">MUSIC</a>
  </nav>

 
  <section id="facebook">
    <h2>facebook</h2> 
    <p>My facebook account</p>
    <a href="https://www.facebook.com/profile.php?id=100077516572274" target="_blank">Facebook</a>
  </section>

  <section id="MUSIC">
    <h2>MUSIC</h2>
    <p>My favorate song</p>
    <a href="https://www.youtube.com/watch?v=XVhEm62Uqog" target="_blank">your favorate to song</a>
    <img class="panda-img" src="edben.jpg" alt="Cute Panda">
    <audio controls> 
    <source src="Ben&Ben - Ben&Ben - Araw-Araw _ Official Music Video.mp3"> 
    </audio>
  </section>

  <section id="features">
    <h2>Photo</h2>
   
    <img class="panda-img" src="jas.jpg" alt="Cute Panda"> 
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>0922 AYG TOO AMAW</p>

    <section id="features">
        <h2>Features</h2>
        <ul>
          <li>Easy to navigate</li>
          <li>Responsive design</li>
          <li>Clean layout</li>
        </ul>
      
        <div class="panda-container">
          <img class="panda-img animated-panda" src="yasmine.jpg" alt="Cute Panda">
        </div>
      </section>
      

    

      </body>
      </html>
