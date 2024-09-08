# ashley-python-portfolio-new
A portfolio showcasing Python projects by Ashley French
/
├── index.html
├── projects/
├── assets/
└── css/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ashley French's Python Portfolio</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Python Portfolio</h1>
        <p>Explore my projects and skills in Python development.</p>
    </header>
    
    <section>
        <h2>Featured Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Project 1: Data Analysis with Pandas</h3>
                <p>A Python project showcasing data analysis and visualization with Pandas and Matplotlib.</p>
                <a href="projects/data-analysis.html">View Project</a>
            </div>
            <div class="project">
                <h3>Project 2: Web Scraping with BeautifulSoup</h3>
                <p>A web scraping project that extracts data from online sources using Python's BeautifulSoup library.</p>
                <a href="projects/web-scraping.html">View Project</a>
            </div>
            <!-- Add more projects as needed -->
        </div>
    </section>
    
    <footer>
        <p>Connect with me on <a href="https://www.linkedin.com/in/ashleyfrench/">LinkedIn</a></p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #0073e6;
    color: white;
    padding: 10px 0;
    text-align: center;
}

.projects {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin: 20px;
}

.project {
    background-color: white;
    padding: 15px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #0073e6;
    color: white;
}
