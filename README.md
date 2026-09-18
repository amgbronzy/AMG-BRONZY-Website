# AMG-BRONZY-Website
<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>AMG BRONZY | Official Website</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #050505;
      color: #ffffff;
      line-height: 1.6;
    }

    header {
      min-height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(135deg, #050505, #171717);
    }

    .hero {
      max-width: 850px;
    }

    .hero h1 {
      font-size: clamp(45px, 10vw, 90px);
      letter-spacing: 5px;
      color: #d4af37;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 20px;
      color: #dddddd;
      margin-bottom: 30px;
    }

    .button {
      display: inline-block;
      padding: 14px 28px;
      border: 2px solid #d4af37;
      color: #d4af37;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
    }

    .button:hover {
      background: #d4af37;
      color: #050505;
    }

    section {
      max-width: 1100px;
      margin: auto;
      padding: 70px 20px;
    }

    h2 {
      text-align: center;
      color: #d4af37;
      font-size: 34px;
      margin-bottom: 35px;
    }

    .about {
      text-align: center;
      max-width: 750px;
      margin: auto;
      color: #cccccc;
      font-size: 18px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .card {
      background: #111111;
      border: 1px solid #333333;
      border-radius: 15px;
      padding: 30px 20px;
      text-align: center;
    }

    .card h3 {
      color: #d4af37;
      margin-bottom: 10px;
    }

    .photo-box {
      min-height: 250px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #111111;
      border: 2px dashed #d4af37;
      border-radius: 15px;
      color: #888888;
      text-align: center;
      padding: 20px;
    }

    .contact {
      text-align: center;
    }

    .contact a {
      color: #d4af37;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      border-top: 1px solid #222222;
      color: #888888;
    }
  </style>

</head>

<body>

  <header>
    <div class="hero">
      <h1>AMG BRONZY</h1>
      <p>Web Design • Coding • Automotive</p>
      <a class="button" href="#about">Explore</a>
    </div>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p class="about">
      Welcome to the official AMG BRONZY website.
      I am passionate about web design, coding, technology,
      and the automotive industry.
    </p>
  </section>

  <section>
    <h2>What I Do</h2>

```
<div class="cards">

  <div class="card">
    <h3>🌐 Web Design</h3>
    <p>Creating modern and attractive websites.</p>
  </div>

  <div class="card">
    <h3>💻 Coding</h3>
    <p>Learning and building digital projects.</p>
  </div>

  <div class="card">
    <h3>🚗 Automotive</h3>
    <p>Buying and selling cars and exploring the automotive world.</p>
  </div>

</div>
```

  </section>

  <section>
    <h2>My Photos</h2>

```
<div class="photo-box">
  📸 Your photo will go here
</div>
```

  </section>

  <section class="contact">
    <h2>Connect With Me</h2>

```
<p>
  Instagram:
  <a href="https://instagram.com/bronzyamg" target="_blank">
    @bronzyamg
  </a>
</p>
```

  </section>

  <footer>
    © 2026 AMG BRONZY. All Rights Reserved.
  </footer>

</body>
</html>
