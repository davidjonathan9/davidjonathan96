<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Pribadi Saya</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8; /* Light Greyish Blue */
        }
        header {
            background: #2c3e50; /* Navy Blue */
            color: #ecf0f1; /* Light Grey */
            padding: 2rem 0;
            text-align: center;
        }
        nav {
            background: #34495e; /* Darker Navy Blue */
            color: #ecf0f1; /* Light Grey */
            padding: 1rem 0;
            text-align: center;
        }
        nav a {
            color: #ecf0f1; /* Light Grey */
            margin: 0 1rem;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #1abc9c; /* Turquoise on Hover */
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        article {
            background: #ffffff; /* White Background for Articles */
            padding: 2rem;
            margin-bottom: 3rem; /* Increased Margin Bottom */
            border-radius: 12px; /* Increased Border Radius */
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1); /* Increased Box Shadow */
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
        img, video, iframe {
            max-width: 30%;
            height: 30%;
            border-radius: 12px; /* Increased Border Radius */
            margin-bottom: 1rem; /* Added Margin Bottom */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Added Box Shadow */
        }
        .profile-picture {
            display: block;
            margin: auto;
            width: 250px;
            height: 200px;
            border-radius: 100%;
            object-fit: cover;
            margin-bottom: 1rem;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.3); /* Added Box Shadow */
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome</h1>
    <img class="profile-picture" src="profil.jpg" alt="Foto Profil">
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
            <p>Welcome To David's Blog.</p>
            <h3>Photo/CV</h3>
            <img src="davdav.jpg" alt="Deskripsi Foto"> <img src="davcv2.jpg" alt="Deskripsi Foto">
            <h3>Video</h3>
            <h3>Link YouTube</h3>
            <p>
                Watch this story telling video on
                <a href="https://youtu.be/XiSbU3dRwFA?feature=shared" target="_blank">YouTube</a>.
            </p>
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
            <p>You can contact me via email davidsekeh96@gmail.com</p>
            <p>Instagram : daviddjonathan</p>
        </article>
    </section>
</div>

</body>
</html>
