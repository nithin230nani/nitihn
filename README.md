# nitihn<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <style>
      body {
        font-family: "Arial", sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f8f9fa;
        color: #343a40;
      }

      header {
        background-color: #007bff;
        color: white;
        text-align: center;
        padding: 2em 0;
      }
      .h1 {
        color: black;
        font-size: 65px;
      }

      section {
        max-width: 800px;
        margin: 2em auto;
        padding: 1em;
        background-color: white;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        border-radius: 8px;
      }

      h1,
      h2,
      h3 {
        color: #007bff;
      }

      p {
        line-height: 1.6;
      }

      .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 1em;
      }

      .skill {
        background-color: #007bff;
        color: white;
        padding: 0.5em 1em;
        border-radius: 4px;
      }

      .skills div:hover {
        transform: scale(1.1);
      }

      .project {
        margin-bottom: 2em;
      }

      .project img {
        max-width: 100%;
        height: auto;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease-in-out;
      }

      .project img:hover {
        transform: scale(1.1);
      }

      .project-description {
        margin-top: 1em;
      }

      .testimonial {
        background-color: #f8f9fa;
        padding: 1em;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        margin-bottom: 1em;
      }

      form {
        max-width: 500px;
        margin: 2em auto;
        background-color: #fff;
        padding: 1em;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      }

      label {
        display: block;
        margin-bottom: 0.5em;
      }

      input,
      textarea {
        width: 100%;
        padding: 0.5em;
        margin-bottom: 1em;
        border: 1px solid #ddd;
        border-radius: 4px;
      }

      button {
        background-color: #007bff;
        color: white;
        padding: 0.5em 1em;
        border: none;
        border-radius: 4px;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <header>
      <h1 class="h1">Nithin</h1>
      <p>Web Developer</p>
    </header>

    <section>
      <h2>About Me</h2>
      <p>
        To work with an organization which offers challenging opportunities, and
        excellent co-operative working environment, enabling me to improve my
        abilities, develop my functionality, and improve the organization plans
        and work procedures.
      </p>
    </section>

    <section>
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill">HTML5</div>
        <div class="skill">CSS3</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Bootstrap</div>
        <div class="skill">mysql</div>
        <div class="skill">React</div>
        <div class="skill">php</div>
        <!-- Add more skills as needed -->
      </div>
    </section>

    <section>
      <h2>My Projects</h2>

      <div class="project">
        <h3>Project Name: E-COMMERCE WEBSITE</h3>
        <img
          src="https://5.imimg.com/data5/EK/EK/JK/SELLER-15664414/clothes-online-e-commerce-website-designing-services-500x500.jpg"
          alt="Project 1 Screenshot"
        />
        <div class="project-description">
          <ul>
            <li>
              Developed userinterface with html, css, javascript and bootstrap
              which imporved user satisfaction.
            </li>
            <li>This are used to create for the client side purpose.</li>
            <li>For server side Sqlplus and php are used.</li>
            <li>
              Learned multiple threading, concurrency, design pattern and tehir
              impacts on applicaton concurrency.
            </li>
            <li>
              Designed and developed different types of web applications using
              javascript frameworks.
            </li>
          </ul>
          <p><br /></p>
          <p><a href="project1-link">View Project</a></p>
        </div>
      </div>

      <!-- Repeat the project structure for additional projects -->
    </section>

    <section>
      <h2>Testimonials</h2>

      <div class="testimonial">
        <p>
          "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam
          facilisis, sapien vitae."
        </p>
        <p><strong>Client Name</strong></p>
      </div>

      <!-- Repeat the testimonial structure for additional testimonials -->
    </section>

    <section>
      <h2>Contact Me</h2>
      <form>
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Your Email</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Your Message</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </body>
</html>
