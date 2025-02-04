<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>My Portfolio</title>
    <style>
        body {
    background-image: url('https://media.giphy.com/media/l1J9IQ6b9EtsW9QFG/giphy.gif');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
    text-align: center; 
}
header, section, ul {
    text-align: left;
    margin: 0 auto;
    max-width: 800px; 
}

.nav-container {
    text-align: left;
}

#win {
    display: flex;
    justify-content: flex-start;
}

#win a {
    margin-right: 20px;
    text-decoration: none;
    color: black;
    font-size: 18px;
}
</style>
    </style>
    <script src="script.js"></script>
    
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const links = document.querySelectorAll('nav a');

            links.forEach(link => {
                link.addEventListener('click', smoothScroll);
            });

            function smoothScroll(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                window.scrollTo({
                    top: targetElement.offsetTop,
                    behavior: 'smooth'
                });
            }
        });
    </script>
</head>
<body>
    <nav>
        <ol>
            <ol>
                <ol>
                    <div id="win">
                        <a href="#About Me">About Me</a>
                        <a href="#Achievement">Achievement</a>
                        <a href="#Contact Me">Contact Me</a>
                    </div>
                </ol>
            </ol>
        </ol>
    </nav>

    <br>
    <header>
        <h1 style="font-size:60px;text-align:center; "><i>My Portfolio</i></h1>
        <div style="flex: 1; text-align: center;">
        <img src="c:\Users\trixie anne estigoy\Downloads\387505442_1399952443889214_4427009279286146208_n.jpg" alt="my image" width="350" height="350">
        </div>
        <br>
        <br>
        <br>
    </header>

<section id="About Me">
    <h2 style="font-size:35px;">About Me</h2>
    <p style="font-size:20px;"><B>Hello! I'm Erwin C. Gaon</B><br></p>

                               <br>
                               <p style="font-size:15px;"> I am thrilled to welcome you into my world of sports excellence. I am a passionate athlete who has dedicated my life to the games of baseball and basketball. Currently, I am proudly representing the University of the Cordilleras on a sports scholarship, a dream come true for me.

        From a young age, I fell in love with the exhilaration of competition and the artistry of these two sports. Baseball, with its timeless traditions and strategic nuances, has always held a special place in my heart. The feel of a baseball glove in my hand, the crack of the bat, and the precision of pitching have become second nature to me. Whether I'm in the outfield tracking down a fly ball or at the plate, every moment on the baseball diamond is an opportunity to showcase my skills.
        
        Basketball, on the other hand, offers a different kind of excitement. The rapid pace, teamwork, and the ability to sink a perfect three-pointer or make a game-changing steal bring out the best in me. Being on the court is like entering a world where anything is possible, and the adrenaline rush of a close game is incomparable.
        
        My journey to the University of the Cordilleras on a sports scholarship has been a testament to my dedication and hard work. The countless hours of practice, the early morning workouts, and the unwavering commitment to improving my game have all paid off. It's an honor to be part of such a prestigious institution that values both academics and athletics.
        
        Beyond the court, I am a dedicated student pursuing WEB TECHNOLOGY. My time at the University of the Cordilleras is not only about excelling in sports but also about furthering my education and personal growth. I believe that the discipline, teamwork, and resilience I've developed in sports will serve me well in all aspects of my life.

        In addition to my athletic and academic pursuits, I am also passionate about giving back to the community. I believe in the power of sports to inspire and uplift others. Whether it's coaching youth teams, organizing sports clinics, or participating in charitable events, I'm always looking for ways to make a positive impact through my love for sports.
        
        As I continue my journey at the University of the Cordilleras, I am excited about the opportunities that lie ahead. I am committed to representing my school with pride and giving my all on the field and court. I look forward to not only growing as an athlete and a student but also as a person who can make a difference in the world.
        
        Thank you for joining me on this incredible adventure, and I can't wait to see what the future holds both in sports and in life. I got it!</p>
</section>

       <ul>
            <li><b> Date of Birth: May, 05 2005</li></b>
            <li><b> HOBBIES</li></b>
               <ul>
                <li>baseball</li>
                <li>basketball</li>
                <li>singing</li>
                <li>dancing</li>
               </ul>
        </ul>
<section id=" Education "></section>
<section id="Education">
    <h2 style="font: size 45px;">Education</h2>
    <div class="Achievement">
<ul>
    <li>University of the Cordilleras(present)</li>
    <li>Baguio City National High School(2017 - 2021)</li>
    <li>Manuel L. Quezon Elementary School(2011-2017)</li>

</ul>
<section id="Achievement">
    <h2 style="font: size 45px;text-align: center;">My Achievement</h2>
    <div class="Achievement">
        <br> 
        <div style="flex: 1; text-align: center;"></div>
        <img src="C:\Users\trixie anne estigoy\Pictures\team.jpg" alt="team" width="800" height="700">  
<p>This is the first time that i win in a game of basketball and my first champion in any sports that i played. It felt so good because the feeling of winning is so much fun but the feeling of losing is much more fun because you can learn about your mistakes and improve. I have the saying that "DON'T GIVE UP , GROW UP".</p></div>
</section>
        
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<section id="Contact Me">
    <h2 style= "font: size 45px;text-align: left;">Contact Me</h2> </P>
  <ul><li>Email: gaonerwin5@gmail.com</li>
    <li>Contact Number: #09556075409</li>
    <li>LinkedIn: LinkedIn Profile</li>
    <li>Facebook: Erwin Gaon</li>
    <li>@ 2023-2024 ERWINGAON</li>
</ul> 

