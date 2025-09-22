<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Discover Our Factory</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto Condensed', sans-serif;
      background: #FFFFFF;
      margin: 0;
      padding: 0;
      color: #7F7F7F;
      text-align: center;
    }
    header {
      position: relative;
      background: #f0f0f0;
      height: 35vh;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }
    header img.logo {
      position: absolute;
      top: 20px;
      left: 20px;
      height: 60px;
    }
    header img.banner {
      width: 100%;
      height: 100%;
      object-fit: cover;
      opacity: 0.6;
    }
    header h1 {
      position: absolute;
      color: #0064AE;
      font-size: 2.5em;
      z-index: 2;
    }
    h2 {
      color: #0064AE;
      margin-top: 40px;
    }
    .doc-links {
      margin: 40px auto;
      max-width: 500px;
    }
    a {
      display: block;
      margin: 15px auto;
      padding: 14px 20px;
      background: #f9f9f9;
      border: 1px solid #7F7F7F;
      border-radius: 6px;
      color: #7F7F7F;
      text-decoration: none;
      font-size: 1.1em;
      transition: all 0.2s ease-in-out;
    }
    a:hover {
      background: #0064AE;
      color: #FFFFFF;
      border-color: #0064AE;
    }
    footer {
      margin: 50px 0 20px;
      font-size: 0.8em;
      color: #7F7F7F;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.jpg" alt="Company Logo" class="logo">
    <img src="banner.png" alt="Banner" class="banner">
    <h1>Discover Our Factory</h1>
  </header>

  <h2>A closer look at the professions and know-how you encountered</h2>

  <div class="doc-links">
    <a href="Draft_Bourdon-visite_BIN_2025.ppsx" download>Download Interactive Presentation (PPSX)</a>
    <a href="factory-presentation.pdf" target="_blank">View PDF (online)</a>
    <a href="extra-materials.zip" download>Extra Materials (optional)</a>
  </div>

  <footer>
    © 2025 Your Company — Hosted on GitHub Pages
  </footer>
</body>
</html>
