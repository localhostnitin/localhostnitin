<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nitin Kumar | .NET Developer</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #f4f6f9;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1000px;
    margin: auto;
}

/* Header */
.header {
    background: linear-gradient(135deg, #0d6efd, #6610f2);
    color: white;
    text-align: center;
    padding: 60px 20px;
}

.profile-header {
    text-align: center;
}

.profile-pic {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid white;
    margin-bottom: 15px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}

.profile-pic:hover {
    transform: scale(1.05);
}

.subtitle {
    margin-top: 10px;
    font-size: 18px;
    opacity: 0.95;
}

/* Cards */
.card {
    background: white;
    margin: 25px auto;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
}

.card h2 {
    margin-bottom: 15px;
    color: #0d6efd;
}

ul {
    line-height: 1.8;
}

/* Tech badges */
.tech-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.badge {
    background: #e7f1ff;
    color: #0d6efd;
    padding: 8px 14px;
    border-radius: 20px;
    font-size: 14px;
    font-weight: 600;
}

/* Projects */
.project {
    margin-bottom: 15px;
}

/* Footer */
.footer {
    text-align: center;
    padding: 20px;
    background: #111;
    color: #bbb;
    margin-top: 40px;
}

/* Responsive */
@media (max-width: 600px) {
    .header h1 {
        font-size: 24px;
    }

    .subtitle {
        font-size: 14px;
    }

    .profile-pic {
        width: 110px;
        height: 110px;
    }
}
</style>
</head>

<body>

<header class="header">
    <div class="container profile-header">
        <!-- 👉 Put your image in same folder and name profile.jpg -->
        <img src="profile.jpg" alt="Nitin Kumar" class="profile-pic">

        <h1>Hi, I'm Nitin Kumar 👋</h1>
        <p class="subtitle">
            Full Stack .NET Developer | ASP.NET Core | React (Beginner) | SQL Server
        </p>
    </div>
</header>

<section class="card container">
    <h2>👨‍💻 About Me</h2>
    <ul>
        <li>✔ 6+ years of experience in .NET development</li>
        <li>✔ Strong in ASP.NET Core, MVC, Web API, C#</li>
        <li>✔ Experience with ADO.NET & Entity Framework Core</li>
        <li>✔ Currently learning React and modern frontend development</li>
        <li>✔ Strong knowledge of SQL Server & T-SQL</li>
        <li>✔ Experience with JWT Authentication & API Security</li>
        <li>✔ Interested in Microservices Architecture</li>
    </ul>
</section>

<section class="card container">
    <h2>🛠️ Tech Stack</h2>
    <div class="tech-grid">
        <span class="badge">C#</span>
        <span class="badge">ASP.NET Core</span>
        <span class="badge">Web API</span>
        <span class="badge">ADO.NET</span>
        <span class="badge">Entity Framework</span>
        <span class="badge">React (Beginner)</span>
        <span class="badge">JavaScript</span>
        <span class="badge">Bootstrap</span>
        <span class="badge">SQL Server</span>
        <span class="badge">JWT</span>
    </div>
</section>

<section class="card container">
    <h2>📌 Featured Projects</h2>

    <div class="project">
        <h3>Member Management System</h3>
        <p>
            Full CRUD application using ASP.NET Core with role-based login,
            ADO.NET, SQL Server, and Razor Views.
        </p>
    </div>

    <div class="project">
        <h3>React Member Update Module</h3>
        <p>
            Modern tabbed UI with responsive Bootstrap design and
            JSON-based dynamic data handling.
        </p>
    </div>
</section>

<section class="card container">
    <h2>🎯 Currently Learning</h2>
    <ul>
        <li>Advanced ASP.NET Core</li>
        <li>Clean Architecture</li>
        <li>Microservices</li>
        <li>System Design</li>
    </ul>
</section>

<footer class="footer">
    <p>© 2026 Nitin Kumar | Full Stack Developer</p>
</footer>

</body>
</html>
