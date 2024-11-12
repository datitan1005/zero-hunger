# zero-hunger
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZERO HUNGER</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 20px; 
            background-image: url('https://www.pixelstalk.net/wp-content/uploads/2016/08/Fruit-Wallpaper-HQ.jpg'); 
            background-size: cover; 
            color: white; /* Ensure text is visible over the background image */
        }
        header { 
            background: rgba(0, 0, 0, 0.5); /* Adding a slight background color for better readability */
            padding: 10px 20px; 
            opacity: 0;
            animation: fadeIn 1s forwards;
        }
        nav ul { 
            list-style-type: none; 
            padding: 0; 
        }
        nav ul li { 
            display: inline; 
            margin-right: 10px; 
        }
        section { 
            margin: 20px 0; 
            padding: 20px; 
            background: rgba(0, 0, 0, 0.5); /* Adding a slight background color for better readability */
            opacity: 0;
        }
        footer { 
            padding: 10px 20px; 
            text-align: center; 
            background: rgba(0, 0, 0, 0.5); /* Adding a slight background color for better readability */
            opacity: 0;
        }
        @keyframes fadeIn {
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>ZERO HUNGER PROJECT, GROUP 3</h1>
        <nav>
            <ul>
                <li><a href="#home" style="color: white;">Home</a></li>
                <li><a href="#about" style="color: white;">About</a></li>
                <li><a href="#contact" style="color: white;">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Home</h2>
        <p>This project aims to address the critical issue of hunger by promoting sustainable practices and innovative solutions. Hunger has been a persistent problem in our continent, with many communities struggling to access nutritious food. Our approach includes utilizing leftovers creatively, educating the public on sustainable food practices, and advocating for policy changes to support food security.</p>
        <p>For instance, using onion peelings to make onion spice, or turning old bananas into delicious banana cake, can significantly reduce food waste and provide nutritious alternatives. By raising awareness and offering practical solutions, we hope to make a tangible impact on reducing hunger in our communities.</p>
        <p>Additionally, our project involves collaborating with students to ensure surplus produce is distributed to those in need rather than going to waste. Together, we can create a future where no one has to go to bed hungry.</p>
    </section>
    <section id="about">
        <h2>About</h2>
        <p>Our project focuses on repurposing fruit leftovers to make nutritious fruit smoothies. This initiative not only reduces food waste but also provides healthy options for our community. We believe that small changes in our daily habits can lead to significant improvements in food security and environmental sustainability.</p>
        <p>In addition to making fruit smoothies, we also teach people about the importance of reducing food waste and how they can contribute to zero hunger efforts. We encourage everyone to share their experiences, spread the word, and participate in our mission to eradicate hunger.</p>
        <h3>Project Video</h3>
        <video width="320" height="240" controls>
            <source src="path/to/your-video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>If you have any questions, suggestions, or want to get involved in our project, please reach out to us. We are always looking for passionate individuals who want to make a difference.</p>
        <p>Email: <a href="mailto:faith.muinura@bihc.ac.ke" style="color: white;">faith.muinura@bihc.ac.ke</a></p>
        <p>Phone: +254 741 679 077 ("for sites issues")</p>
    </section>
    <footer>
        <p>&copy; 2024 BY KENTA MBOYANO. All rights reserved.</p>
    </footer>

    <script>
        document.addEventListener("DOMContentLoaded", () => {
            const sections = document.querySelectorAll('section');
            const footer = document.querySelector('footer');

            sections.forEach((section, index) => {
                setTimeout(() => {
                    section.style.animation = `fadeIn 1s forwards`;
                }, (index + 1) * 500); // Stagger the animations by 1 second each
            });

            setTimeout(() => {
                footer.style.animation = `fadeIn 1s forwards`;
            }, (sections.length + 1) * 500);
        });
    </script>
</body>
</html>

