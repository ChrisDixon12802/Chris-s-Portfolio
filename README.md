<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="styles.css" class="styles" />
  </head>
  <body>
    <div class="main-container">
      <nav class="navbar">
        <ul>
          <li class="home"><a href="#">Home</a></li>
          <li class="about"><a href="#">About Me</a></li>
          <li class="projects"><a href="#">Projects</a></li>
          <li class="contact"><a href="#">Contact</a></li>
        </ul>
      </nav>

  <section class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Hello! My name is Chris and I'm an up-and-coming web developer.</p>

  <p class="goal">
          My passion is creating websites that are not only user-friendly but
          also the best a website can possibly be in terms of design and
          functionality. I want to make sure that every website I make is the
          best for any business or any individual that would need a website
          made.
        </p>
        <img
          src="images/screenshot-2025-10-30-161620.png"
          alt="Portfolio screenshot"
        />
      </section>

   <section class="projects">
        <h2>My Projects</h2>
          <div class="project">
            <img
              src="images/screenshot-2025-10-30-161620.png"
              alt="Project 1 screenshot"
            />
            <h3>Project 1</h3>
            <p class="project1">
              My first ever project that I started was a simple website just for
              fun just to see what I could do with HTML and CSS.
            </p>
          </div>
          <div class="project">
            <img
              src="images/screenshot-2025-10-30-161620.png"
              alt="Project 2 screenshot"
            />
            <h3>Project 2</h3>
            <p class="project2">
              and for my second project i decided to text out how i could use
              html and css to make the website more appealing.
            </p>
          </div>
          <div class="project">
            <img
              src="images/screenshot-2025-10-30-161620.png"
              alt="Project 3 screenshot"
            />
            <h3>Project 3</h3>
            <p class="project3">
              as for my third project i decided to test out how i could use html
              and css to make the website more appealing. adding hover effect
              and other things to make the website look better.
            </p>
          </div>
          </div>
        </div>
      </section>
    </div>

 <footer class="footer">
      <p>Privacy policy | Terms of service | Contact Info</p>
    </footer>
  </body>
</html>

.navbar {
  background-color: rgb(0, 0, 0);
  overflow: hidden;
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 50px;
  box-sizing: border-box;
  margin: -8px;
  margin-right: -32px;
  margin-left: -8px;
  flex-wrap: wrap;
}

.navbar ul {
  list-style: none;
  margin: 0%;
  padding: 10px;
  display: flex;
  align-items: center;
  cursor: pointer;
}
.navbar a {
  padding: 14px 20px;
  text-decoration: none;
  color: rgb(255, 255, 255);
  display: inline-block;
}
.li {
  margin-right: auto;
  margin-left: auto;
  gap: 8px;
  padding: 14px 20px;
}
.navbar a:hover {
  color: rgb(132, 217, 245);
}
.hero {
  background-color: rgb(132, 217, 245);
  padding: 20px;
  margin-top: 8px;
  min-height: 400px;
  width: 100%;
  margin-left: -8px;
  margin-right: -32px;
  overflow: hidden;
}
h1 {
  color: rgb(0, 0, 0);
  text-align: center;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 38px;
}
p {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 20px;
  color: black;
  text-align: center;
  margin-top: 20px;
  margin-bottom: 20px;
  text-align: center;
  width: 80%;
  margin-left: auto;
  margin-right: auto;
}
.me {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 20px;
  color: rgb(0, 0, 0);
  text-align: center;
  margin-top: 20px;
  margin-bottom: 20px;
  text-align: center;
  width: 80%;
  margin-left: auto;
  margin-right: auto;
}
footer {
  cursor: pointer;
}
footer p {
  text-align: center;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  color: rgb(0, 0, 0);
  padding: 10px;
  margin-top: 728px;
  box-sizing: border-box;
  justify-content: space-between;
  width: 100%;
  margin-left: -10px;
  margin-right: -50px;
}
h2 {
  text-align: center;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 28px;
}
