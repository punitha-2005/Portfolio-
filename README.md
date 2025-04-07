<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Resume with Photo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 20px;
    }

    .resume {
      background: #fff;
      max-width: 800px;
      margin: auto;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }

    .header {
      display: flex;
      align-items: center;
      border-bottom: 2px solid #ddd;
      padding-bottom: 20px;
    }

    .header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 20px;
    }

    .header .info {
      flex: 1;
    }

    .header .info h1 {
      margin: 0;
    }

    .header .info p {
      color: #666;
      font-size: 14px;
    }

    .section {
      margin-top: 30px;
    }

    .section h2 {
      border-left: 4px solid #007BFF;
      padding-left: 10px;
      font-size: 20px;
      color: #333;
    }

    ul {
      padding-left: 20px;
    }

    .section p, .section li {
      font-size: 15px;
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <div class="resume">
    <div class="header">
      <img src="your-photo.jpg" alt="Your Photo" />
      <!-- Replace 'your-photo.jpg' with your image path -->
      <div class="info">
        <h1>Punithavathi S</h1>
        <p>Email: punithavathi@gmail.com | </p>
      </div>
    </div>

    <div class="section">
      <h2>Profile</h2>
      <p>I am a student of Bharathiyar university. I am pursuing degree in this university.I have studied programming language like c,c++,java.</p>
    </div>

    <div class="section">
      <h2>Skills</h2>
      <ul>
        <li>HTML, CSS</li>
        <li>Javascript</li>
        <li>Python</li>
      </ul>
    </div>

    <div class="section">
      <h2>Project</h2>
        <li>College portal</li>
        <li>Cloud computing IBM</li>
      </ul>
    </div>

    <div class="section">
      <h2>Education</h2>
      <p><strong>Bachelor of Science in Computer Science</strong><br>Bharathiyar University</p>
    </div>
  </div>
</body>
</html>
