<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PIONEER TUITION AND HOME SCHOOLING - ELDORET</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff;
      color: #000;
    }

    header {
      background-color: #000;
      color: gold;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
      text-transform: uppercase;
    }

    header p {
      margin: 5px 0 0;
      font-style: italic;
      color: #fff;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background-color: gold;
    }

    nav a {
      padding: 14px 20px;
      text-decoration: none;
      color: black;
      font-weight: bold;
      transition: background 0.3s;
    }

    nav a:hover {
      background-color: black;
      color: gold;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      border-bottom: 2px solid gold;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }

    .programs ul {
      list-style-type: square;
      padding-left: 20px;
    }

    form input,
    form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form button {
      background-color: black;
      color: gold;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      font-weight: bold;
    }

    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.5rem;
      }

      nav a {
        flex: 1 1 100%;
        text-align: center;
      }
    }

    /* Hide second form */
    .hidden {
      display: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>PIONEER TUITION AND HOME SCHOOLING – ELDORET</h1>
    <p>“Timely learning at the comfort of your home”</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#programs">Programs</a>
    <a href="#enrollment">Enrollment</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome</h2>
    <p>At PIONEER TUITION AND HOME SCHOOLING – ELDORET, we provide quality, personalized education to learners in the comfort of their homes. Our experienced tutors focus on holistic development and academic excellence through structured, flexible programs.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>We are a team of passionate educators based in Eldoret, committed to delivering structured home-based learning tailored to each child's needs. Our mission is to make quality education accessible and convenient for all families.</p>
  </section>

  <section id="programs" class="programs">
    <h2>Our Programs</h2>
    <ul>
      <li>Early Childhood Education (Ages 3–6)</li>
      <li>Primary School Tutoring (Grades 1–8)</li>
      <li>KCPE & KCSE Exam Preparation</li>
      <li>Subject-Specific Support (Math, Science, English, etc.)</li>
      <li>Holiday Revision and Remedial Lessons</li>
    </ul>
  </section>

  <section id="enrollment">
    <h2>Enrollment</h2>
    <p>Ready to start? Contact us to schedule an assessment and customize your child's learning plan. We accept students year-round and offer flexible payment plans.</p>
    <p>
      <strong>Call/WhatsApp:</strong><br>
      +254721512202<br>
      +254794814146<br>
      <strong>Emails:</strong><br>
      vilmajebet490@gmail.com<br>
      kipkorirenock62@gmail.com
    </p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <!-- Main Form (to vilmajebet490) -->
    <form id="mainForm" action="https://formsubmit.co/vilmajebet490@gmail.com" method="POST" onsubmit="copyToSecondForm()">
      <input type="hidden" name="_captcha" value="false">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>

    <!-- Hidden Second Form (to kipkorirenock62) -->
    <form id="secondaryForm" class="hidden" action="https://formsubmit.co/kipkorirenock62@gmail.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="text" name="name" />
      <input type="email" name="email" />
      <textarea name="message"></textarea>
    </form>
  </section>

  <footer>
    &copy; 2025 PIONEER TUITION AND HOME SCHOOLING – ELDORET. All rights reserved.
  </footer>

  <script>
    function copyToSecondForm() {
      const main = document.getElementById("mainForm");
      const second = document.getElementById("secondaryForm");

      second.name.value = main.name.value;
      second.email.value = main.email.value;
      second.message.value = main.message.value;

      setTimeout(() => {
        second.submit();
      }, 100);
    }
  </script>

</body>
</html>
