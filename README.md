# BrixAshley.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Social Media Manager Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins',sans-serif;
    }

    body{
      background:#0d0d0d;
      color:#f5f5f5;
      min-height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      padding:40px;
    }

    .container{
      width:100%;
      max-width:1100px;
      background:#161616;
      border:1px solid #2d2d2d;
      border-radius:20px;
      padding:60px;
      box-shadow:0 0 30px rgba(0,0,0,0.5);
    }

    nav{
      display:flex;
      justify-content:space-between;
      align-items:center;
      margin-bottom:80px;
    }

    .logo{
      font-size:24px;
      font-weight:700;
      color:#ffffff;
      letter-spacing:1px;
    }

    .nav-links{
      display:flex;
      gap:30px;
    }

    .nav-links a{
      text-decoration:none;
      color:#bdbdbd;
      font-size:15px;
      transition:0.3s ease;
    }

    .nav-links a:hover{
      color:#ffffff;
    }

    .hero{
      display:flex;
      flex-direction:column;
      gap:25px;
    }

    .tag{
      color:#9f9f9f;
      font-size:14px;
      letter-spacing:2px;
      text-transform:uppercase;
    }

    h1{
      font-size:64px;
      line-height:1.1;
      max-width:700px;
    }

    h1 span{
      color:#8a8a8a;
    }

    .description{
      color:#b8b8b8;
      max-width:650px;
      line-height:1.8;
      font-size:16px;
    }

    .buttons{
      margin-top:20px;
      display:flex;
      gap:20px;
      flex-wrap:wrap;
    }

    .btn{
      padding:14px 28px;
      border-radius:12px;
      text-decoration:none;
      font-weight:500;
      transition:0.3s ease;
    }

    .primary{
      background:#f5f5f5;
      color:#000;
    }

    .primary:hover{
      background:#d6d6d6;
    }

    .secondary{
      border:1px solid #444;
      color:#fff;
    }

    .secondary:hover{
      background:#222;
    }

    .socials{
      margin-top:60px;
      display:flex;
      gap:20px;
      flex-wrap:wrap;
    }

    .socials a{
      width:55px;
      height:55px;
      display:flex;
      justify-content:center;
      align-items:center;
      border-radius:14px;
      background:#1e1e1e;
      color:#ffffff;
      font-size:20px;
      text-decoration:none;
      border:1px solid #333;
      transition:0.3s ease;
    }

    .socials a:hover{
      transform:translateY(-5px);
      background:#2a2a2a;
    }

    footer{
      margin-top:70px;
      color:#777;
      font-size:14px;
    }

    @media(max-width:768px){

      .container{
        padding:35px;
      }

      nav{
        flex-direction:column;
        gap:20px;
      }

      .nav-links{
        gap:15px;
        flex-wrap:wrap;
        justify-content:center;
      }

      h1{
        font-size:42px;
      }
    }
  </style>
</head>
<body>

  <div class="container">

    <nav>
      <div class="logo">BRIX.</div>

      <div class="nav-links">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Portfolio</a>
        <a href="#">Contact</a>
      </div>
    </nav>

    <section class="hero">

      <p class="tag">Social Media Manager</p>

      <h1>
        Building <span>strong brands</span> through creative social media strategies.
      </h1>

      <p class="description">
        I help businesses grow their online presence through engaging content,
        audience growth strategies, brand management, and high-performing social media campaigns.
      </p>

      <div class="buttons">
        <a href="#" class="btn primary">View Portfolio</a>
        <a href="#" class="btn secondary">Hire Me</a>
      </div>

      <div class="socials">

        <!-- Instagram -->
        <a href="https://instagram.com/yourusername" target="_blank">
          <i class="fab fa-instagram"></i>
        </a>

        <!-- Email -->
        <a href="mailto:your@email.com">
          <i class="fas fa-envelope"></i>
        </a>

        <!-- WhatsApp -->
        <a href="https://wa.me/639000000000" target="_blank">
          <i class="fab fa-whatsapp"></i>
        </a>

        <!-- LinkedIn -->
        <a href="https://linkedin.com/in/yourusername" target="_blank">
          <i class="fab fa-linkedin-in"></i>
        </a>

      </div>

    </section>

    <footer>
      © 2026 Brix Ashley Nuñez — Social Media Manager
    </footer>

  </div>

</body>
</html>
