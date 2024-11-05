<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Profile - AI & Web Developer</title>
  <style>
    /* Global Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      color: #333;
      line-height: 1.6;
      background: #f4f4f9;
    }

    /* Profile Header */
    .profile-header {
      background-image: url('header-image.png'); /* Use your profile header image here */
      background-size: cover;
      background-position: center;
      text-align: center;
      color: #fff;
      padding: 80px 20px;
    }

    .profile-header h1 {
      font-size: 2.5em;
      margin-bottom: 0.5em;
    }

    .profile-header p {
      font-size: 1.2em;
    }

    /* Section Styles */
    .about, .skills, .projects, .contact {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }

    h2 {
      font-size: 1.8em;
      margin-bottom: 10px;
      color: #333;
    }

    .about p, .contact p {
      font-size: 1.1em;
    }

    /* Skills Section */
    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skills li {
      background: #0066cc;
      color: #fff;
      padding: 8px 15px;
      border-radius: 5px;
      font-size: 0.9em;
    }

    /* Projects Table */
    .projects table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    .projects th, .projects td {
      padding: 12px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }

    .projects th {
      background-color: #004080;
      color: #fff;
      font-weight: 700;
    }

    .projects td {
      background-color: #e6f2ff;
      color: #333;
    }

    /* Contact Section */
    .contact {
      text-align: center;
    }

    .contact-btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      color: #fff;
      background-color: #0080ff;
      border-radius: 5px;
      text-decoration: none;
    }

    .contact-btn:hover {
      background-color: #0059b3;
    }
  </style>
</head>
<body>

  <!-- Profile Header with Background Image -->
  <header class="profile-header">
    <div class="header-content">
      <h1>AI & ML Expert | Hardware-Software Integrator | Web Developer</h1>
      <p>Turning innovative ideas into reality. Over 100+ projects successfully delivered!</p>
    </div>
  </header>

  <!-- About Section -->
  <section class="about">
    <h2>About Me</h2>
    <p>I am a tech enthusiast specializing in AI, Machine Learning, and web development. My expertise extends to integrating hardware and software solutions, and I have delivered numerous successful projects that have helped clients worldwide.</p>
  </section>

  <!-- Skills Section -->
  <section class="skills">
    <h2>Skills</h2>
    <ul>
      <li>Machine Learning & AI Development</li>
      <li>Hardware-Software Integration</li>
      <li>Full-Stack Web Development</li>
      <li>Project Consultation & Support</li>
    </ul>
  </section>

  <!-- Projects Sold Table -->
  <section class="projects">
    <h2>Projects Sold</h2>
    <table>
      <thead>
        <tr>
          <th>Project Name</th>
          <th>Category</th>
          <th>Sales Count</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Smart Home AI System</td>
          <td>AI/Hardware</td>
          <td>35</td>
        </tr>
        <tr>
          <td>Stock Prediction Model</td>
          <td>Machine Learning</td>
          <td>48</td>
        </tr>
        <tr>
          <td>E-Commerce Website</td>
          <td>Web Development</td>
          <td>72</td>
        </tr>
        <tr>
          <td>Health Monitoring Wearable</td>
          <td>IoT/Hardware</td>
          <td>29</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Contact Section -->
  <section class="contact">
    <h2>Contact Me</h2>
    <p>Feel free to reach out for collaborations, freelance projects, or consultations!</p>
    <a href="mailto:youremail@example.com" class="contact-btn">Contact via Email</a>
  </section>

</body>
</html>
