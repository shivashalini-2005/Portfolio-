# Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Resume with Photo</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f0f2f5;
    }
    .resume {
      display: flex;
      max-width: 1000px;
      margin: 40px auto;
      background: #fff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .sidebar {
      background: #2c3e50;
      color: #fff;
      padding: 30px;
      width: 30%;
      text-align: center;
    }
    .sidebar img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 3px solid #fff;
    }
    .sidebar h2 {
      margin: 10px 0;
    }
    .sidebar p, .sidebar li {
      font-size: 14px;
      line-height: 1.6;
    }
    .main {
      padding: 30px;
      width: 70%;
    }
    .main h1 {
      margin-top: 0;
      color: #2c3e50;
    }
    .main .title {
      color: #555;
      margin-bottom: 20px;
    }
    .section {
      margin-bottom: 25px;
    }
    .section h2 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
      margin-bottom: 10px;
      color: #2c3e50;
    }
    ul {
      padding-left: 20px;
    }
  </style>
</head>
<body>

<div class="resume">
  <div class="sidebar">
    <img src="your-photo.jpg" alt="Profile Photo" />
    <h2>Shivashalini A</h2>
    <p>Computer Science student</p>
    <hr style="border: 0; border-top: 1px solid #fff; margin: 20px 0;">
    <h3>Contact</h3>
    <p>Email: shivashalini@gmail.com</p>
    <p>Phone: 9876543210</p>

    <h3>Skills</h3>
    <ul style="list-style-type: none; padding: 0;">
      <li>HTML/CSS</li>
      <li>JavaScript</li>
      <li>C & C++</li>
      <li>Python</li>
    </ul>
  </div>

  <div class="main">
    <h1>Shivashalini A</h1>
    <p class="title">Computer Science student</p></p>

    <div class="section">
      <h2>Profile</h2>
      <p>I'm a Student of Bharathiar University. I am pursuing BSc CS degree in this university. I have studied Programming Languages like Java, C++ and C. I have one more year to complete My degree. I am very eager to work in IT companies. My wish is to get a job in abroad with a good salary.</p>
    </div>

    <div class="section">
      <h2>Project</h2>
      <ul>
        <li>Cloud computing IBM</li>
        <li>College portal</li>
      </ul>


    <div class="section">
      <h2>Education</h2>
      <p><strong>Bachelor of Science in Computer Science</strong><br>Bharathiar University </p>
    </div>
  </div>
</div>

</body>
</html>
