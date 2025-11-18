<html>
<head>
    <title>SYEVITA AISYAH</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #000000;
            line-height: 1.6;
        }
        header {
            background-color: #000000;
            color: #ffffff;
            padding: 50px 20px;
            text-align: center;
            position: relative;
        }
        .profile-frame {
            width: 150px;
            height: 150px;
            border: 5px solid #ffffff;
            border-radius: 50%;
            overflow: hidden;
            margin: 0 auto 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
            animation: fadeIn 1s ease-in;
        }
        .profile-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        h1 {
            margin: 10px 0;
            font-size: 2.5em;
            font-weight: bold;
        }
        .subtitle {
            font-size: 1.2em;
            opacity: 0.8;
        }
        section {
            padding: 60px 20px;
            max-width: 800px;
            margin: 0 auto;
            animation: fadeInUp 1s ease-out;
        }
        section:nth-child(even) {
            background-color: #f5f5f5; /* Subtle gray for contrast */
        }
        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            border-bottom: 2px solid #000000;
            padding-bottom: 10px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }
        li::before {
            content: '■';
            color: #000000;
            position: absolute;
            left: 0;
        }
        .contact a {
            color: #000000;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @media (max-width: 600px) {
            h1 { font-size: 2em; }
            .profile-frame { width: 120px; height: 120px; }
        }
    </style>
</head>
<body>
    <header>
        <div class="profile-frame">
            <img src="profil.jpeg" alt="Profile Picture">
        </div>
        <h1>SYEVITA AISYAH</h1>
        <p class="subtitle">Teknologi Informasi | Politeknik Mercusuar Indonesia</p>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p>Perkenalkan, saya vita lahir di Bojonegoro, 27 September 2006.</p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Microsoft Office</li>
            <li>Copywritting</li>
            <li>Html, css, js, python (basic)</li>
        </ul>
    </section>
    <section id="experience">
        <h2>Experience</h2>
        <ul>
            <li><strong>Coppy writter</strong> 2022 - create content plans, create articles, create social media captions.</li>
            <li><strong>Social media admin</strong> 2022 - posting client content, optimizing client accounts, replying to customer DMs on client accounts, making final reports on performance during the time held by the company</li>
            <li><strong>waitress</strong> 2025 - serving customers, handling complaints, backing up cashiers</li>
        </ul>
    </section>
    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>Get in touch: <a href="mailto:vtmakertrsr@gmail.com">Email</a> | <a href="https://www.instagram.com/vloraa.rmy/" target="_blank">Instagram</a> | <a href="https://github.com/vlomy" target="_blank">GitHub</a></p>
    </section>
    <footer>
        <p>&copy; 2025 Syevita.</p>
    </footer>
</body>
</html>
