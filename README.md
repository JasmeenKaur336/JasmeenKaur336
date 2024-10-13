<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jasmeen's Portfolio</title>
    <style>
        /* Reset default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f4f8;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            padding: 20px;
            text-align: center;
            color: white;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ffdd57; /* Highlight color on hover */
        }

        section {
            padding: 50px;
            text-align: center;
            margin: 20px;
            border-radius: 10px;
            background-color: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        h1, h2 {
            color: #333;
            margin-bottom: 20px;
        }

        /* Styling for project cards */
        .project-card {
            display: inline-block;
            width: calc(33% - 40px);
            margin: 20px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: scale(1.05); /* Scale up on hover */
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
            }

            .project-card {
                width: calc(100% - 40px); /* Full width on smaller screens */
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Jasmeen's Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Introduction</h2>
        <ul style="list-style-type: none; padding: 0;">
            <li><strong>Name:</strong> Jasmeen Kaur</li>
            <li><strong>Profession:</strong> Passionate Freelancer</li>
            <li><strong>Primary Skill:</strong> Python</li>
            <li><strong>Language Proficiency:</strong> IELTS Band 7.5</li>
            <li><strong>Creativity:</strong> Innovative thinker with a knack for generating ideas</li>
            <li><strong>Aspiration:</strong> Eager to build exciting projects in the tech industry</li>
        </ul>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <ul style="list-style-type: none; padding: 0;">
            <li><strong>Education:</strong>
                <ul>
                    <li>Master’s in Computer Applications from Punjabi University Patiala</li>
                    <li>Bachelor’s in Science (Non-Medical) from Punjabi University Patiala</li>
                </ul>
            </li>
            <li><strong>Certifications:</strong>
                <ul>
                    <li>Introduction to HTML (SoloLearn)</li>
                    <li>Introduction to SQL (SoloLearn)</li>
                    <li>Classroom Management (Ratna Sagar)</li>
                    <li>Participation in National Space Day Quiz (ISRO & MyGov)</li>
                    <li>Data Visualization: Empowering Business with Effective Insights (Foroge, TATA)</li>
                </ul>
            </li>
            <li><strong>Teaching Experience:</strong>
                <ul>
                    <li>Teacher at Sparkling Kids: The Foundation School, Patran (Oct 2023 - Mar 2024)</li>
                    <li>Home Tutor (Apr 2020 - Mar 2021)</li>
                </ul>
            </li>
            <li><strong>Career Goals:</strong> Keen interest in developing a career as a coder and creating impactful projects.</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>Website Development</h3>
            <p>Created a responsive website using HTML, CSS, and JavaScript to showcase personal projects.</p>
        </div>
        <div class="project-card">
            <h3>Simple Chatbot</h3>
            <p>Developed a simple chatbot using Python that can answer basic questions and provide information.</p>
        </div>
        <div class="project-card">
            <h3>Data Visualization Tool</h3>
            <p>Built a tool using Python and libraries like Matplotlib to visualize data and provide insights.</p>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <p>Python, Data Structures and Algorithms (DSA) in C++, HTML, CSS</p>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required style="padding: 10px; margin: 10px 0; width: 80%; border-radius: 5px; border: 1px solid #ccc;">
            <input type="email" placeholder="Your Email" required style="padding: 10px; margin: 10px 0; width: 80%; border-radius: 5px; border: 1px solid #ccc;">
            <textarea placeholder="Your Message" style="padding: 10px; margin: 10px 0; width: 80%; border-radius: 5px; border: 1px solid #ccc;"></textarea>
            <button type="submit" style="padding: 10px 20px; border: none; background-color: #6a11cb; color: white; border-radius: 5px; cursor: pointer;">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Jasmeen Kaur. All rights reserved.</p>
    </footer>
</body>
</html>
