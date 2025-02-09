# HTML-Introductory-
<!DOCTYPE html>
<html lang="en">
<head>
    <link href="https://fonts.googleapis.com/css2?family=Lora:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alina Mishra - Autobiography</title>
    <style>
        body {
            background-color: #f8f9fa; /* Light background color for whole document */
        }
        .section-spacing {
            margin-bottom: 40px; /* Adding spacing between sections */
        }
        h2 {
            background-color: #d1ecf1; /* Light blue background for headings */
            padding: 10px;
            border-radius: 5px;
        }
        .welcome-heading {
            background-color: #fff5ee; /* Light red background */
            padding: 15px;
            border-radius: 10px;
        }
        .gallery img {
            max-width: 80%; /* Reducing size of first image */
            display: block;
            margin: 0 auto;
        }
        .table {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <a class="navbar-brand" href="#">Alina Mishra</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#achievements">Achievements</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#goals">Goals</a></li>
                    <li class="nav-item"><a class="nav-link" href="#hobbies">Hobbies</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#footer">Contact</a></li>
                </ul>
            </div>
        </nav>
        <h1 class="text-center text-danger my-4 display-4 welcome-heading">Welcome to Alina's Autobiography</h1>
    </header>

    <main class="container my-5">
        <section id="about" class="section-spacing">
            <h2 class="text-primary">About Me</h2>
            <p class="text-info bg-light p-3 rounded">Hello, I am Alina Mishra, a passionate and driven Computer Science student currently residing in Nova Scotia, Canada. My academic journey has taken me from Amity University, India, to Acadia University, Nova Scotia, where I am completing my Bachelor’s in Computer Science as a 3rd-year transfer student. My dedication to innovation and learning has been the cornerstone of my personal and professional growth.I was born in New Delhi, India, on December 09, 2004. I am the eldest child, and my younger brother is 4 years younger than me. I have lived my whole life in New Delhi before moving to Nova Scotia, Canada, for my further studies.</p>
            <p class="text-danger bg-light p-3 rounded">I grew up in a Brahmin family where my mother and father worked in multinational companies. From them, I developed multiple skills such as communication and presentation skills. I also enhanced my self-confidence and the ability to present speeches fluently with their guidance.As an adolescent, I was an active member of my high school student council and received many achievements in English debates and declamation competitions. In high school, I pursued STEAM with science as my major, including Physics, Chemistry, Math, English, and Computer Science as my main subjects. I planned to join a Bachelor's in Computer Science for my post-secondary education and enrolled in a transfer program at Amity University, India, to a Canadian university </p>
            <p class="text-success bg-light p-3 rounded">During my university days in India, I developed various skills and joined multiple research and educational part-time jobs. I worked as a research intern in reinforcement learning in cybersecurity in 2023 and as a research assistant in face recognition and artificial intelligence in 2024. Additionally, I gained marketing experience as an intern at the Younity Organization, worked as a guest teacher in an educational organization, and volunteered as a tech and event organizer at the Reinvorgate Foundation, a nonprofit NGO. September 2024, I moved to Nova Scotia, Canada, to complete the remainder of my studies at Acadia University, Wolfville, where I joined as a 3rd-year student in Computer Engineering. The exposure to abroad studies and culture has been a great part of my life, allowing me to develop skills such as managing a lifestyle while engaging in studies and part-time work. It has been a fantastic journey so far!</p>
        </section>

        <section id="achievements" class="section-spacing">
            <h2 class="text-primary">My Achievements</h2>
            <table class="table table-striped table-bordered">
                <thead class="thead-dark">
                    <tr>
                        <th>Area</th>
                        <th>Achievements</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Programming Proficiency</td>
                        <td>Earned a certificate in "Programming for Everyone with Python" from the University of Michigan.</td>
                    </tr>
                    <tr>
                        <td>Professional Excellence</td>
                        <td>"Best Presenter and Star Performer" award during my internship at Unity Group.</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section id="projects" class="section-spacing">
            <h2 class="text-primary">My Projects</h2>
            <table class="table table-striped table-bordered">
                <thead class="thead-dark">
                    <tr>
                        <th>Project</th>
                        <th>Details</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>CIO&Leader Project</td>
                        <td>Contributed to the "CIO&Leader" app development project, enhancing front-end design and debugging.</td>
                    </tr>
                    <tr>
                        <td>ARIZONE25 Project</td>
                        <td>Led the "ARIZONE25" project, fostering mentorship among students.</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section id="goals" class="section-spacing">
            <h2 class="text-primary">My Goals</h2>
            <ul>
                <li>Pursue a challenging role in software development and research.</li>
                <li>Contribute to the advancement of AI in education and sustainability.</li>
                <li>Develop innovative technologies to improve learning outcomes.</li>
            </ul>
        </section>

        <section id="hobbies" class="section-spacing">
            <h2 class="text-primary">My Hobbies</h2>
            <ul>
                <li>Exploring robotics and LEGO-based innovations.</li>
                <li>Advocating sustainability through educational initiatives.</li>
                <li>Studying learning theories and creativity techniques.</li>
            </ul>
        </section>

        <section id="experience" class="section-spacing">
            <h2 class="text-primary">My Professional and Volunteer Experience</h2>
            <h3>Professional Experience</h3>
            <ul>
                <li>Research Intern (May 2023 – July 2023): Reinforcement learning in cybersecurity.</li>
                <li>Research Assistant (May 2024 – July 2024): Face detection using AI.</li>
                <li>Marketing Intern (April 2023 – August 2023): Market research and client outreach.</li>
                <li>Guest Teacher (April 2024 – August 2024): Taught Computer Science.</li>
            </ul>
            <h3>Volunteer Experience</h3>
            <ul>
                <li>Event Organizer: Led multiple events at Amity University.</li>
                <li>Tech and Event Organizer: Volunteered for 2 years at Reinvorgate Foundation.</li>
            </ul>
        </section>

        <section id="gallery" class="section-spacing">
            <h2 class="text-primary">Gallery</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <img src="image1.jpg" class="img-fluid rounded shadow gallery" alt="Photo of Alina">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="image2.jpg" class="img-fluid rounded shadow" alt="Photograph of Certificate">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="image3.jpg" class="img-fluid rounded shadow" alt="Photograph of my favorite moment">
                </div>
            </div>
        </section>
    </main>

    <footer id="footer" class="bg-dark text-white text-center py-3 mt-5">
        <p>Contact: alina.mishra1979@gmail.com</p>
        <p>&copy; 2025 Alina Mishra</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
