<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Justice League Guide</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Roboto', sans-serif; margin: 0; padding: 0; background-color: #e0e0e0; color: #333; }
        header { background-color: #1a237e; color: white; padding: 1em 0; text-align: center; position: fixed; width: 100%; top: 0; z-index: 1000; }
        nav ul { list-style: none; padding: 0; margin: 0; text-align: center; }
        nav ul li { display: inline; }
        nav ul li a { text-decoration: none; color: white; padding: 10px 15px; transition: background-color 0.3s; }
        nav ul li a:hover { background-color: #0d47a1; }
        main { padding-top: 60px; text-align: center; }
        h1, h2, h3 { font-family: 'Montserrat', sans-serif; text-decoration: underline; }
        section { margin-bottom: 2em; padding: 1em; background-color: #ffffff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); border-radius: 8px; }
        .character { background-color: #eeeeee; color: #333; padding: 20px; border-left: 5px solid #1a237e; }
        .button { background-color: #0d47a1; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; display: inline-block; transition: background-color 0.3s, transform 0.2s; }
        .button:hover { background-color: #1a237e; transform: translateY(-2px); }
        iframe { width: 100%; max-width: 800px; height: 450px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        footer { background-color: #1a237e; color: white; text-align: center; padding: 1em 0; position: relative; width: 100%; }
        @media (max-width: 600px) { nav ul li a { padding: 8px 10px; } }
    </style>
</head>
<body>
    <header>
        <h1>The Justice League Guide</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#characters">Characters</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="mailto:Mrtfarrell3@gmail.com">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main id="home">
        <section>
            <h1>Welcome to the World of Heroes</h1>
            <p>Explore the incredible powers and abilities of DC Universe's characters. Learn about your favorite heroes and villains, their origins, and their unique abilities.</p>
            <a href="#characters" class="button">Discover Characters</a>
        </section>
        <section>
            <h2>Trailer for the Justice League Movie</h2>
            <iframe src="https://www.youtube.com/embed/g_6yBZKj-eo?si=Meq7adIH_srrzoGQ" frameborder="0" allowfullscreen></iframe>
        </section>
        <section id="characters">
            <h2>Meet the Justice League Members</h2>
            <div id="superman" class="character">
                <h3>Superman</h3>
                <p>Superman, also known as the Man of Steel, possesses incredible powers, including superhuman strength, flight, invulnerability, super speed, heat vision, and x-ray vision. His alter ego is Clark Kent, a mild-mannered reporter for the Daily Planet.</p>
            </div>
            <div id="batman" class="character">
                <h3>Batman</h3>
                <p>Batman, also known as Bruce Wayne, possesses genius-level intellect and is a master of martial arts, using his skills to combat crime in Gotham City.</p>
            </div>
            <div id="martian-manhunter" class="character">
                <h3>Martian Manhunter</h3>
                <p>Martian Manhunter, also known as J'onn J'onzz, has powers including telepathy, shape-shifting, intangibility, and invisibility.</p>
            </div>
            <div id="wonder-woman" class="character">
                <h3>Wonder Woman</h3>
                <p>Wonder Woman, princess Diana of Themyscira, is equipped with superhuman strength, agility, and the Lasso of Truth.</p>
            </div>
            <div id="the-flash" class="character">
                <h3>The Flash</h3>
                <p>The Flash, the fastest man alive, uses his speed to manipulate time and space, helping him to fight crime and uphold justice.</p>
            </div>
            <div id="aquaman" class="character">
                <h3>Aquaman</h3>
                <p>Aquaman, ruler of Atlantis, uses his aquatic abilities to patrol the world’s oceans and command all sea life.</p>
            </div>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>This page is designed to provide information about the members of the Justice League and their powers, highlighting their roles and special abilities.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 The Justice League Guide. All rights reserved.</p>
    </footer>
</body>
</html>
</html>
