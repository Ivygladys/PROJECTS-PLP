# PROJECTS-PLP
I am Ivy Wanjiru and I chose to take on three projects because I thrive in dynamic environments, and engaging with multiple initiatives aligns with both my personal and professional aspirations. Having diverse interests—from interior architecture and design to Selfcare and business —has naturally led me to pursue multiple projects. Each one offers unique challenges and opportunities for growth, which I find essential for my learning process.

Additionally, balancing different projects helps me stay motivated. I have AudHD, which means I work best when I can channel my energy into various creative and strategic activities. It’s also in line with my values of making meaningful contributions across sectors—whether through my involvement in all the above. This approach ensures I don’t put all my efforts into one basket, giving me room to pivot or adapt if one project faces challenges.

Lastly, I believe these projects complement each other and align with my broader goals in business administration, love for selfcare, and construction. Taking this path allows me to apply concepts from my MBA coursework, CPA studies, and practical experience in real-time while building something sustainable. Each project serves a unique part of my vision, whether it’s contributing to climate justice, growth. By diversifying, I increase my chances of long-term success and avoid burnout by shifting focus when needed.

Below are my projects.

BuildTracker
BuildTracker is an innovative platform designed to streamline project management and enhance collaboration among teams. Its user-friendly interface allows project managers and team members to track progress, set deadlines, and allocate resources effectively. With features like task assignments, time tracking, and real-time updates, BuildTracker empowers teams to meet their goals efficiently. The platform supports various industries, making it adaptable for diverse project needs. By fostering transparency and accountability, BuildTracker enhances productivity, ensuring that projects are delivered on time and within budget.

Inclusion Hub
Inclusion Hub is a dedicated space that champions diversity, equity, and inclusion in communities and workplaces. It provides resources, training, and advocacy to promote understanding and acceptance among individuals of different backgrounds. The Hub organizes workshops, events, and discussions to raise awareness about the importance of inclusivity, empowering participants to become agents of change. By fostering a supportive environment, Inclusion Hub aims to break down barriers and create equitable opportunities for all, driving social progress and encouraging collaboration across diverse groups.

That Girl Oasis
That Girl Oasis is a vibrant self-care hub designed to empower individuals on their wellness journeys. This inclusive space offers resources, community support, and personalized tools for holistic well-being. Members can engage in activities like journaling, meditation, and goal-setting, fostering a culture of self-love and personal growth. The hub features a user-friendly dashboard to track self-care activities, maintain a wellness log, and access a comprehensive checklist for daily practices. With a focus on mental, emotional, and physical health, That Girl Oasis inspires individuals to prioritize their well-being and embrace a balanced lifestyle.


[Uploading F<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>That Girl</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f3f3f3;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 20px 0;
            background-color: #fff;
            width: 100%;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
        }

        header h1 {
            color: #ff9bcb;
            font-size: 2.5rem;
            margin: 0;
        }

        .container {
            width: 100%;
            max-width: 800px;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
            margin: 20px 0;
            opacity: 0;
            transform: translateX(-100%);
            transition: opacity 0.5s ease, transform 0.5s ease;
        }

        .visible {
            opacity: 1;
            transform: translateX(0);
        }

        .hidden {
            display: none;
        }

        input[type="text"], input[type="email"], input[type="password"], textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        input[type="submit"], .btn {
            background: #ff9bcb;
            color: #fff;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            width: 100%;
            text-align: center;
            text-decoration: none;
            margin: 10px 0;
        }

        input[type="submit"]:hover, .btn:hover {
            background: #ff76a6;
        }

        nav {
            margin-bottom: 20px;
        }

        nav a {
            color: #ff9bcb;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .log-entry {
            background: #f9f9f9;
            padding: 10px;
            margin: 10px 0;
            border-left: 5px solid #ff9bcb;
        }

        .checklist {
            margin: 20px 0;
        }

        .checklist input {
            margin-right: 10px;
        }

        @media (max-width: 768px) {
            body {
                justify-content: flex-start;
            }

            .container {
                padding: 10px;
            }

            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Your Self-Maintenance Hub</h1>
        <nav>
            <a href="#" onclick="showSection('home')">Home</a>
            <a href="#" onclick="showSection('profile')">Profile</a>
            <a href="#" onclick="showSection('dashboard')">Dashboard</a>
            <a href="#" onclick="showSection('maintenanceLog')">Maintenance Log</a>
            <a href="#" onclick="showSection('checklist')">Checklist</a> <!-- New Checklist Link -->
        </nav>
    </header>

    <!-- Home Section -->
    <div class="container" id="home">
        <img src="c:\Users\user\Downloads\54f66680e03c26ac0bd582010ae85ea22.jpg" alt="image" width="800" height="150">
        <h2>Welcome to your self-maintenance journey!</h2>
        <p>Select an option from the navigation above to get started.</p>
    </div>

    <!-- Profile Section -->
    <div class="container hidden" id="profile">
        <h2>Your Profile</h2>
        <form id="profileForm">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Full Name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Email" required>

            <input type="submit" value="Update Profile">
        </form>
    </div>

    <!-- Dashboard Section -->
    <div class="container hidden" id="dashboard">
        <img src="c:\Users\user\Downloads\de5156ba2bcffc180e5a0b3b3703ce600.jpg" alt="image" width="795" height="150">
        <h2>Dashboard</h2>
        <p>Here’s an overview of your recent activities and goals.</p>
        <ul>
            <li>Self-Care Activities Completed: <strong>5</strong></li>
            <li>Goals Achieved: <strong>2</strong></li>
            <li>Next Goal: <strong>Read a Book</strong></li>
        </ul>
    </div>

    <!-- Maintenance Log Section -->
    <div class="container hidden" id="maintenanceLog">
        <img src="c:\Users\user\Downloads\3cd45de63b6f0604621003cbc6c264e77.jpg" alt="image" width="795" height="150">
        <h2>Maintenance Log</h2>
        <form id="logForm">
            <label for="activity">Activity:</label>
            <textarea id="activity" name="activity" placeholder="Describe your self-care activity..." required></textarea>

            <input type="submit" value="Add Log Entry">
        </form>
        <h3>Your Log Entries</h3>
        <div id="logEntries">
            <!-- Example log entry -->
            <div class="log-entry">
                <p><strong>Activity:</strong> Meditated for 10 minutes</p>
                <p><strong>Date:</strong> September 3, 2024</p>
            </div>
        </div>
    </div>

    <!-- Checklist Section -->
    <div class="container hidden" id="checklist">
        <h2>Self-Maintenance Checklist</h2>
        <div class="checklist">
            <label><input type="checkbox"> Drink Water</label><br>
            <label><input type="checkbox"> Take a Walk</label><br>
            <label><input type="checkbox"> Meditate</label><br>
            <label><input type="checkbox"> Read a Book</label><br>
            <label><input type="checkbox"> Journal</label><br>
        </div>
    </div>

    <script>
        // Function to switch between sections
        function showSection(sectionId) {
            // Hide all sections
            const sections = document.querySelectorAll('.container');
            sections.forEach(section => {
                section.classList.remove('visible');
                section.classList.add('hidden');
            });

            // Show the selected section with slide animation
            const activeSection = document.getElementById(sectionId);
            activeSection.classList.remove('hidden');
            setTimeout(() => {
                activeSection.classList.add('visible');
            }, 10); // Slight delay to trigger CSS transition
        }

        // Handle profile form submission
        document.getElementById('profileForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Profile updated!');
        });

        // Handle maintenance log form submission
        document.getElementById('logForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const activity = document.getElementById('activity').value;
            const logEntries = document.getElementById('logEntries');

            // Create new log entry
            const logEntry = document.createElement('div');
            logEntry.classList.add('log-entry');
            logEntry.innerHTML = `<p><strong>Activity:</strong> ${activity}</p><p><strong>Date:</strong> ${new Date().toLocaleDateString()}</p>`;

            // Add log entry to the logEntries div
            logEntries.appendChild(logEntry);

            // Clear the textarea
            document.getElementById('activity').value = '';

            alert('Log entry added!');
        });

        // Initialize with the home section visible
        showSection('home');
    </script>
</body>
</html>
inal project selfcare {That girl} wonyoungism inspired.html…]()

[Uploading// server.js
const express = require('express');
const bodyParser = require('body-parser');
const path = require('path');

const app = express();
const PORT = process.env.PORT || 3000;

// Middleware
app.use(bodyParser.urlencoded({ extended: true }));
app.use(bodyParser.json());
app.use(express.static('public')); // Serve static files from 'public' directory

// Serve the main HTML file
app.get('/', (req, res) => {
    res.sendFile(path.join(__dirname, 'public', 'index.html'));
});

// Handle profile form submission
app.post('/update-profile', (req, res) => {
    // Here you can save the profile data to a database or perform other actions
    console.log('Profile updated:', req.body);
    res.json({ message: 'Profile updated successfully!' });
});

// Handle log entry submission
app.post('/add-log', (req, res) => {
    // Save log entry to database or perform other actions
    console.log('Log entry added:', req.body);
    res.json({ message: 'Log entry added successfully!' });
});

// Start the server
app.listen(PORT, () => {
    console.log(`Server is running on http://localhost:${PORT}`);
});
 That girl backend.js…]()


 [Uploadi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="InclusionHub is a platform for financial inclusion, connecting individuals with essential services and educational resources.">
    <meta name="keywords" content="financial inclusion, community support, banking services, education, microfinance">
    <title>InclusionHub - Financial Inclusion Platform</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #e6f7ff;
        }

        header {
            background: #003366;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            padding: 20px;
        }

        section {
            margin: 20px 0;
            padding: 20px;
            background: #ffffff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        footer {
            text-align: center;
            padding: 10px;
            background: #003366;
            color: #ffffff;
            position: relative;
            width: 100%;
            bottom: 0;
            margin-top: 20px;
        }

        /* Styles for forms and buttons */
        form {
            display: flex;
            flex-direction: column;
        }

        label {
            margin-top: 10px;
        }

        input[type="text"],
        input[type="email"],
        input[type="number"],
        textarea {
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            margin-top: 10px;
            padding: 10px;
            background: #003366;
            color: #ffffff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background: #002244;
        }

        /* Styles for testimonials */
        .testimonial {
            background: #f9f9f9;
            padding: 15px;
            border-left: 4px solid #003366;
            margin: 10px 0;
        }

        /* Styles for financial services list */
        .service {
            background: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            margin: 10px 0;
            transition: 0.3s;
        }

        .service:hover {
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        @media (max-width: 600px) {
            nav ul {
                display: flex;
                flex-direction: column;
                align-items: center;
            }
            nav ul li {
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header><img src="c:\Users\user\Downloads\money 21.jpg" alt="InclusionHub Logo" >

        <h1>InclusionHub</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Financial Services</a></li>
                <li><a href="#education">Education Resources</a></li>
                <li><a href="#budgeting">Budgeting</a></li>
                <li><a href="#calculator">Budget Calculator</a></li>
                <li><a href="#community">Community Forum</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About InclusionHub</h2>
            <p>InclusionHub is a digital platform dedicated to promoting financial inclusion by connecting individuals and small businesses with essential financial services, educational resources, and community support. Our mission is to empower those underserved by traditional banking systems.</p>
        </section>

        <section id="services">
            <h2>Financial Services Directory</h2>
            <div class="service">
                <h3>Local Banks</h3>
                <p>Find local banks that offer accounts with no minimum balance requirements and low fees.</p>
            </div>
            <div class="service">
                <h3>Credit Unions</h3>
                <p>Explore community-oriented credit unions that provide loans and savings products.</p>
            </div>
            <div class="service">
                <h3>Microfinance Institutions</h3>
                <p>Access microfinance options tailored for entrepreneurs and small businesses in your area.</p>
            </div>
            <div class="service">
                <h3>Fintech Solutions</h3>
                <p>Discover innovative fintech apps that offer financial services through your smartphone.</p>
            </div>
        </section>

        <section id="education">
            <h2>Educational Resources</h2>
            <p>Enhance your financial literacy with our comprehensive educational materials:</p>
            <ul>
                <li>Budgeting Tips</li>
                <li>Saving Strategies</li>
                <li>Understanding Credit</li>
                <li>Investment Basics</li>
            </ul>
            <p>Join our webinars and workshops to learn directly from financial experts!</p>
        </section>

        <section id="budgeting">
            <h2>In-Depth Budgeting</h2>
            <p>Budgeting is essential for managing your finances effectively. Here are steps to create a practical budget:</p>
            <ol>
                <li><strong>Identify Your Income:</strong> List all sources of income including salaries, freelance work, and passive income.</li>
                <li><strong>Track Your Expenses:</strong> Keep a record of all your expenses for a month to see where your money goes.</li>
                <li><strong>Categorize Expenses:</strong> Divide expenses into fixed (rent, utilities) and variable (food, entertainment) categories.</li>
                <li><strong>Set Financial Goals:</strong> Determine short-term and long-term financial goals such as saving for a vacation or retirement.</li>
                <li><strong>Create Your Budget:</strong> Allocate a specific amount to each category based on your income and goals.</li>
                <li><strong>Monitor and Adjust:</strong> Review your budget regularly and adjust as needed to stay on track.</li>
            </ol>
            <p>Utilize budgeting tools and apps to simplify the tracking process and stay organized!</p>
        </section>

        <section id="calculator">
            <h2>Budget Calculator</h2>
            <p>Use our Budget Calculator to find out how much money you have left after expenses.</p>
            <form id="budgetCalculator">
                <label for="income">Monthly Income:</label>
                <input type="number" id="income" name="income" required>

                <label for="fixedExpenses">Total Fixed Expenses:</label>
                <input type="number" id="fixedExpenses" name="fixedExpenses" required>

                <label for="variableExpenses">Total Variable Expenses:</label>
                <input type="number" id="variableExpenses" name="variableExpenses" required>

                <button type="submit">Calculate Remaining Budget</button>
            </form>
            <p id="result" style="margin-top: 15px; font-weight: bold;"></p>
        </section>

        <section id="community">
            <h2>Community Forum</h2>
            <p>Engage with others in your community by sharing experiences, asking questions, and offering support. Join discussions about financial challenges and solutions!</p>
            <form id="forumForm">
                <label for="forumName">Your Name:</label>
                <input type="text" id="forumName" name="forumName" required>
                <label for="forumMessage">Message:</label>
                <textarea id="forumMessage" name="forumMessage" required></textarea>
                <button type="submit">Post Message</button>
            </form>
        </section>

        <section id="testimonials">
            <h2>What Our Users Say</h2>
            <div class="testimonial">
                <p>"InclusionHub helped me find a local credit union that offered me a loan to start my small business!"</p>
                <p>- Sarah J.</p>
            </div>
            <div class="testimonial">
                <p>"The financial education resources are incredibly helpful, especially for someone new to managing their finances."</p>
                <p>- Mark T.</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contactForm">
                <label for="contactName">Name:</label>
                <input type="text" id="contactName" name="contactName" required>
                <label for="contactEmail">Email:</label>
                <input type="email" id="contactEmail" name="contactEmail" required>
                <label for="contactMessage">Message:</label>
                <textarea id="contactMessage" name="contactMessage" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 InclusionHub. All rights reserved.</p>
    </footer>

    <script>
        // Contact Form Submission
        document.getElementById('contactForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Thank you for contacting us, ' + document.getElementById('contactName').value + '! We will get back to you soon.');
            this.reset(); // Reset the form after submission
        });

        // Forum Form Submission
        document.getElementById('forumForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Your message has been posted, ' + document.getElementById('forumName').value + '!');
            this.reset(); // Reset the forum form after submission
        });

        // Budget Calculator Submission
        document.getElementById('budgetCalculator').addEventListener('submit', function(event) {
            event.preventDefault();
            const income = parseFloat(document.getElementById('income').value);
            const fixedExpenses = parseFloat(document.getElementById('fixedExpenses').value);
            const variableExpenses = parseFloat(document.getElementById('variableExpenses').value);
            const remainingBudget = income - (fixedExpenses + variableExpenses);
            document.getElementById('result').innerText = 'Remaining Budget: $' + remainingBudget.toFixed(2);
        });
    </script>
</body>
</html>
ng Final project business {inclusionhub}.html…]()


[Upl// server.js
const express = require('express');
const bodyParser = require('body-parser');
const path = require('path');

const app = express();
const PORT = process.env.PORT || 3000;

// Middleware
app.use(bodyParser.json());
app.use(bodyParser.urlencoded({ extended: true }));
app.use(express.static(path.join(__dirname, 'public')));

// Serve the main HTML file
app.get('/', (req, res) => {
    res.sendFile(path.join(__dirname, 'public', 'index.html'));
});

// Handle contact form submission
app.post('/contact', (req, res) => {
    const { contactName, contactEmail, contactMessage } = req.body;
    console.log(`Contact Form Submission: ${contactName}, ${contactEmail}, ${contactMessage}`);
    res.json({ message: 'Thank you for contacting us! We will get back to you soon.' });
});

// Handle forum message submission
app.post('/forum', (req, res) => {
    const { forumName, forumMessage } = req.body;
    console.log(`Forum Message: ${forumName}: ${forumMessage}`);
    res.json({ message: 'Your message has been posted!' });
});

// Start the server
app.listen(PORT, () => {
    console.log(`Server is running on http://localhost:${PORT}`);
});
oading backend inclusionhub.js…]()



[Upl<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BuildTracker - Your Ultimate Construction Partner</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5dc; /* Beige background */
        }

        header {
            background-color: #d2b48c; /* Tan */
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            padding: 20px;
        }

        section {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h2 {
            border-bottom: 2px solid #d2b48c;
            padding-bottom: 10px;
        }

        .project-image {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin-top: 10px;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #d2b48c; /* Tan */
            color: white;
            position: relative;
            width: 100%;
            bottom: 0;
        }

        form {
            display: flex;
            flex-direction: column;
            margin-top: 10px;
        }

        input[type="text"], input[type="email"], input[type="date"], textarea {
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            padding: 10px;
            margin-top: 10px;
            background-color: #d2b48c; /* Tan */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #c5a06d; /* Dark tan */
        }

        .blog-post {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #d2b48c;
            border-radius: 5px;
            transition: 0.3s;
        }

        .blog-post:hover {
            background-color: #f5f5dc; /* Light beige */
        }

        .testimonial {
            background-color: #ffe4c4; /* Bisque */
            padding: 15px;
            border-left: 5px solid #d2b48c;
            margin: 10px 0;
        }

        @media (max-width: 600px) {
            nav ul li {
                display: block;
                margin: 5px 0;
            }
        }

        .analytics {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            margin: 20px 0;
        }

        .analytics div {
            flex: 1;
            margin: 10px;
            padding: 20px;
            background-color: #f0e68c; /* Light khaki */
            border-radius: 5px;
            text-align: center;
        }

        .chart {
            height: 100px;
            width: 100%;
            background-color: #e0e0e0;
            border-radius: 5px;
            position: relative;
        }

        .progress {
            position: absolute;
            height: 100%;
            background-color: #d2b48c;
        }

        .image-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .image-grid img {
            flex: 1 1 calc(33.33% - 10px);
            border-radius: 5px;
            max-width: 100%;
            height: auto;
        }

        /* Quantity Surveyor Section */
        .quantity-survey-form {
            display: flex;
            flex-direction: column;
            margin-top: 20px;
        }

        .quantity-survey-form input {
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .cost-display {
            margin-top: 20px;
            padding: 15px;
            background-color: #ffe4c4; /* Bisque */
            border-radius: 5px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <img src="c:\Users\user\Downloads\b411.jpg" alt="Header Image" width="1200" height="250">  <!-- Local Image Reference -->
        <h1>BuildTracker</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#analytics">Analytics</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#quantity-survey">Quantity Survey</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to BuildTracker</h2>
            <p>Your ultimate solution for managing construction projects effectively. Track progress, communicate with your team, and stay on schedule.</p>
            <img src="c:\Users\user\Downloads\b.jpg" alt="Construction Site" class="project-image" width="300" height="400">
        </section>

        <section id="projects">
            <h2>Project Management</h2>
            <form id="projectForm">
                <label for="projectName">Project Name:</label>
                <input type="text" id="projectName" name="projectName" required>
                <label for="projectDescription">Description:</label>
                <textarea id="projectDescription" name="projectDescription" required></textarea>
                <label for="projectDeadline">Deadline:</label>
                <input type="date" id="projectDeadline" name="projectDeadline" required>
                <button type="submit">Add Project</button>
            </form>
            <div id="projectList"></div>
        </section>

        <section id="blog">
            <h2>Latest Blog Posts</h2>
            <div class="blog-post">
                <h3>5 Tips for Effective Construction Project Management</h3>
                <p>Learn essential tips to streamline your project management processes and enhance productivity...</p>
                <a href="#">Read more</a>
            </div>
            <div class="blog-post">
                <h3>Innovative Construction Materials for Sustainable Building</h3>
                <p>Explore the latest trends in sustainable materials that are shaping the future of construction...</p>
                <a href="#">Read more</a>
            </div>
        </section>

        <section id="analytics">
            <h2>Project Analytics</h2>
            <div class="analytics">
                <div>
                    <h3>Total Projects</h3>
                    <div class="chart">
                        <div class="progress" style="width: 80%;"></div>
                    </div>
                    <p>8 out of 10 projects active</p>
                </div>
                <div>
                    <h3>Tasks Completed</h3>
                    <div class="chart">
                        <div class="progress" style="width: 60%;"></div>
                    </div>
                    <p>60% tasks completed</p>
                </div>
                <div>
                    <h3>Pending Tasks</h3>
                    <div class="chart">
                        <div class="progress" style="width: 40%;"></div>
                    </div>
                    <p>40% pending tasks</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contactForm">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Your Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>

        <section id="testimonials">
            <h2>Testimonials</h2>
            <div class="testimonial">
                <p>"BuildTracker has transformed the way we manage our construction projects. Highly recommend!" - John D.</p>
            </div>
            <div class="testimonial">
                <p>"The analytics dashboard is a game-changer for tracking our project performance." - Sarah K.</p>
            </div>
        </section>

        <section id="image-gallery">
            <h2>Project Gallery</h2>
            <div class="image-grid">
                <img src="c:\Users\user\Downloads\b3.jpg" alt="Project Image 1" width="300" height="400">
                <img src="c:\Users\user\Downloads\b2.jpg" alt="Project Image 2" width="300" height="400">
                <img src="c:\Users\user\Downloads\b1.jpg" alt="Project Image 3" width="300" height="400">
            </div>
        </section>

        <!-- Quantity Surveyor Section -->
        <section id="quantity-survey">
            <h2>Quantity Survey - Calculate Material and Labor Costs</h2>
            <form class="quantity-survey-form" id="surveyForm">
                <!-- Materials -->
                <label for="materialCost">Total Material Cost (in USD):</label>
                <input type="number" id="materialCost" placeholder="Enter total material cost" required>

                <label for="materialQty">Total Quantity of Materials:</label>
                <input type="number" id="materialQty" placeholder="Enter total quantity of materials" required>

                <!-- Labor -->
                <label for="laborCost">Labor Cost per Hour (in USD):</label>
                <input type="number" id="laborCost" placeholder="Enter labor cost per hour" required>

                <label for="laborHours">Total Labor Hours:</label>
                <input type="number" id="laborHours" placeholder="Enter total labor hours" required>

                <button type="submit">Calculate Total Cost</button>
            </form>

            <!-- Display the total cost -->
            <div id="costDisplay" class="cost-display" style="display:none;">
                <p id="totalCostText">Total Cost:</p>
            </div>
        </section>

    </main>

    <script>
        // Calculate the total cost when the form is submitted
        document.getElementById('surveyForm').addEventListener('submit', function(event) {
            event.preventDefault();

            // Get input values
            const materialCost = parseFloat(document.getElementById('materialCost').value);
            const materialQty = parseFloat(document.getElementById('materialQty').value);
            const laborCost = parseFloat(document.getElementById('laborCost').value);
            const laborHours = parseFloat(document.getElementById('laborHours').value);

            // Calculate the total costs
            const totalMaterialCost = materialCost * materialQty;
            const totalLaborCost = laborCost * laborHours;
            const totalCost = totalMaterialCost + totalLaborCost;

            // Display the result
            document.getElementById('costDisplay').style.display = 'block';
            document.getElementById('totalCostText').innerText = `Total Cost: $${totalCost.toFixed(2)}`;
        });
    </script>
</body>
</html>

oading Final project construction {buildtracker}.html…]()

[Up// File: server.js
const http = require('http');

// In-memory storage for projects and survey data
let projects = [];
let surveyResults = [];

// Helper function to parse request body
const parseBody = (req) => {
    return new Promise((resolve, reject) => {
        let body = '';
        req.on('data', chunk => (body += chunk));
        req.on('end', () => {
            try {
                resolve(JSON.parse(body));
            } catch (error) {
                reject(error);
            }
        });
    });
};

// Create and start the server
const server = http.createServer(async (req, res) => {
    // Enable CORS
    res.setHeader('Access-Control-Allow-Origin', '*');
    res.setHeader('Access-Control-Allow-Methods', 'GET, POST, OPTIONS');
    res.setHeader('Access-Control-Allow-Headers', 'Content-Type');

    // Handle preflight OPTIONS request for CORS
    if (req.method === 'OPTIONS') {
        res.writeHead(204);
        return res.end();
    }

    // GET /projects - Retrieve all projects
    if (req.url === '/projects' && req.method === 'GET') {
        res.writeHead(200, { 'Content-Type': 'application/json' });
        return res.end(JSON.stringify({ projects }));
    }

    // POST /projects - Add a new project
    if (req.url === '/projects' && req.method === 'POST') {
        try {
            const { projectName, projectDescription, projectDeadline } = await parseBody(req);

            if (!projectName || !projectDescription || !projectDeadline) {
                res.writeHead(400, { 'Content-Type': 'application/json' });
                return res.end(JSON.stringify({ message: 'All fields are required.' }));
            }

            const newProject = { id: projects.length + 1, projectName, projectDescription, projectDeadline };
            projects.push(newProject);

            res.writeHead(201, { 'Content-Type': 'application/json' });
            return res.end(JSON.stringify({ message: 'Project added.', project: newProject }));
        } catch {
            res.writeHead(500, { 'Content-Type': 'application/json' });
            return res.end(JSON.stringify({ message: 'Error processing request.' }));
        }
    }

    // POST /survey - Calculate and store survey data
    if (req.url === '/survey' && req.method === 'POST') {
        try {
            const { materialCost, materialQty, laborCost, laborHours } = await parseBody(req);

            if (isNaN(materialCost) || isNaN(materialQty) || isNaN(laborCost) || isNaN(laborHours)) {
                res.writeHead(400, { 'Content-Type': 'application/json' });
                return res.end(JSON.stringify({ message: 'All fields must be valid numbers.' }));
            }

            const totalMaterialCost = materialCost * materialQty;
            const totalLaborCost = laborCost * laborHours;
            const totalCost = totalMaterialCost + totalLaborCost;

            const surveyResult = { id: surveyResults.length + 1, totalMaterialCost, totalLaborCost, totalCost };
            surveyResults.push(surveyResult);

            res.writeHead(201, { 'Content-Type': 'application/json' });
            return res.end(JSON.stringify({ message: 'Survey data processed.', result: surveyResult }));
        } catch {
            res.writeHead(500, { 'Content-Type': 'application/json' });
            return res.end(JSON.stringify({ message: 'Error processing request.' }));
        }
    }

    // Handle 404 - Not Found
    res.writeHead(404, { 'Content-Type': 'application/json' });
    res.end(JSON.stringify({ message: 'Endpoint not found.' }));
});

// Start the server on port 3000
const PORT = 3000;
server.listen(PORT, () => {
    console.log(`Server running at http://localhost:${PORT}/`);
});

loading Buidtracker backend.js…]()






