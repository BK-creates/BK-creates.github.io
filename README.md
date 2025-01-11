<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            display: flex;
            background-color: #2c2c2c;
            border-radius: 10px;
            overflow: hidden;
            max-width: 1200px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
        }
        .sidebar {
            background-color: #333;
            padding: 20px;
            width: 300px;
            text-align: center;
        }
        .sidebar img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
        }
        .sidebar h2 {
            margin: 10px 0;
        }
        .sidebar .contact-info {
            margin-top: 20px;
        }
        .sidebar .contact-info p {
            margin: 10px 0;
        }
        .main-content {
            padding: 20px;
            width: 100%;
        }
        .main-content .section {
            margin-bottom: 30px;
        }
        .main-content h1 {
            border-bottom: 2px solid #ff0;
            display: inline-block;
            padding-bottom: 5px;
        }
        .main-content .cards {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            background-color: #444;
            padding: 20px;
            border-radius: 10px;
            flex: 1;
            min-width: 250px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        }
        .card h3 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="sidebar">
            <img src="profile.jpg" alt="Profile Picture">
            <h2>Barath Kumar S</h2>
            <p>Full Stack Developer</p>
            <div class="contact-info">
                <p>Email: mailtobarathkumars@gmail.com</p>
                <p>Phone: +91 1234567890</p>
                <p>Location: City, Country</p>
            </div>
        </div>
        <div class="main-content">
            <div class="section">
                <h1>About Me</h1>
                <p>Hi, I'm Barath Kumar S, a Full Stack Developer who loves building user-friendly and efficient applications. I enjoy working on both the frontend and backend, bringing ideas to life with modern tools and technologies.</p>
                <p>I'm always eager to learn, solve problems, and build projects that make a difference. Whether it's improving functionality or enhancing the user experience, I love taking on new challenges and growing as a developer.</p>
            </div>
            <div class="section">
                <h1>What I'm Doing</h1>
                <div class="cards">
                    <div class="card">
                        <h3>Frontend Development</h3>
                        <p>Building responsive, user-friendly interfaces using modern frameworks and technologies.</p>
                    </div>
                    <div class="card">
                        <h3>Backend Development</h3>
                        <p>Building and optimizing server-side architecture, APIs, and databases to ensure seamless and scalable application performance.</p>
                    </div>
                    <div class="card">
                        <h3>Cloud/DevOps</h3>
                        <p>Managing cloud infrastructure, automation, and deployment pipelines to ensure reliability and scalability.</p>
                    </div>
                    <div class="card">
                        <h3>Mobile Apps</h3>
                        <p>Developing cross-platform mobile applications using React Native for seamless user experiences across iOS and Android.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>

