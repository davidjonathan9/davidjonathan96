<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Pribadi Saya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8; /* Light Greyish Blue */
        }
        header {
            background: #2c3e50; /* Navy Blue */
            color: #ecf0f1; /* Light Grey */
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #34495e; /* Darker Navy Blue */
            color: #ecf0f1; /* Light Grey */
            padding: 0.5rem 0;
            text-align: center;
        }
        nav a {
            color: #ecf0f1; /* Light Grey */
            margin: 0 1rem;
            text-decoration: none;
        }
        nav a:hover {
            color: #2c3e50; /* Navy Blue on Hover */
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        article {
            background: #ffffff; /* White Background for Articles */
            padding: 2rem;
            margin-bottom: 1rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2, h3 {
            color: #2c3e50; /* Navy Blue */
        }
        p {
            color: #34495e; /* Darker Navy Blue Text */
        }
        footer {
            background: #2c3e50; /* Navy Blue */
            color: #ecf0f1; /* Light Grey */
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        video {
            max-width: 50%;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="home">
        <article>
            <h2>Hello,</h2>
            <p>Welcome To my Blog.</p>
            <h3>Photo</h3>
            <img src="davfoto.jpg" alt="Deskripsi Foto">
            <h3>Video</h3>
            <video controls>
                <source src="TEAM 1.mp4" type="video/mp4">
                Browser Anda tidak mendukung tag video.
            </video>
        </article>
    </section>

    <section id="about">
        <article>
            <h2>About Me</h2>
            <p>Hi, I'm David Jonathan Sekeh and usually called David, and now I will tell about myself.
                I was born in Manado on June 9, 2005, grew up in Tomohon but when I was little I often 
                stayed in Tembagapura, Papua with my grandparents who worked there. When I grew up, I lived in 
                Tomohon city until now. I graduated from Christian Vocational High School 1 Tomohon and I 
                am currently studying and becoming a student at Politeknik Negeri Manado with a major in 
                electrical engineering in the informatics engineering study program. After I graduate, 
                I hope to work in a place that suits my passion. But for now, I hope to get a job even if 
                it's just a part-time job to fill my free time or holidays later.
            </p>
        </article>
    </section>

    <section id="contact">
        <article>
            <h2>Contact</h2>
            <p>Anda bisa menghubungi saya di email@example.com.</p>
        </article>
    </section>
</div>

<footer>
    <p>Blog Pribadi Saya &copy; 2024</footer>

</body>
</html>
