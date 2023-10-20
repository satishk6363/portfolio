<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="C:\Users\Dell\Desktop\portfolio\portfolio.html\style.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>I am Ammula Satish Kumar, currently pursuing my B.Tech in Computer Science and Engineering. I am passionate about learning and improving my skills in web development. I specialize in building responsive and user-friendly websites using HTML, CSS, and JavaScript.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>
          <h3>Website for a local coffee shop</h3>
          <p>This website was built for a local coffee shop. It includes features such as a menu, online ordering, and a blog.</p>
          <a href="https://example.com/coffee-shop">View Website</a>
        </li>
        <li>
          <h3>Portfolio website for a web developer</h3>
          <p>This website was built for a web developer to showcase their work and skills.</p>
          <a href="https://example.com/web-developer">View Website</a>
        </li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form action="/contact" method="post">
        <input type="text" name="name" placeholder="Your Name">
        <input type="email" name="email" placeholder="Your Email">
        <textarea name="message" placeholder="Your Message"></textarea>
        <input type="submit" value="Submit">
      </form>
    </section>
  </main>

  <footer>
    <p>Copyright &copy; 2023 My Portfolio</p>
  </footer>
</body>
</html>
