🛡️ Cyber Shield
Friendly Guide to Online Safety
Cyber Shield is a modern, interactive web platform designed to empower users with the knowledge and tools needed to safely navigate the digital world, focusing on common scams and online threats. It features practical lessons, real-life scam stories, and an AI-powered analyzer for suspicious messages.

This project was built using HTML5, CSS3, and Bootstrap 5.3 with a custom dark, glassmorphic design aesthetic.

🚀 Features
Custom Dark/Glassmorphic UI: A unique, engaging, and modern dark-mode design using custom CSS variables and Bootstrap utilities.

Guides & Lessons (learn.html): Short, actionable tips covering phishing, OTP safety, UPI scams, and recovery checklists.

AI Analyzer (analyzer.html): A tool (conceptual) where users can paste messages to get an instant risk score and red-flag analysis.

Real Stories (stories.html): True incidents of scams for practical learning.

Simulator (simulator.html): Interactive scenarios to practice spotting fraudulent messages safely.

Dedicated Login Page (login.html): A professionally styled login interface maintaining the project's aesthetic.

⚙️ Technology Stack
Frontend: HTML5, CSS3

Framework: Bootstrap v5.3 (CDN)

Styling: Custom CSS for dark theme, glassmorphism, and animated decorative elements (blobs).

Fonts: Inter (via Google Fonts)

📂 Project Structure
This is the expected file structure for the current state of the project:

cyber-shield-project/
├── index.html          # Homepage with the main features and hero section
├── login.html          # Dedicated Login page
├── learn.html          # (Placeholder) Guides & Lessons content
├── stories.html        # (Placeholder) Real Stories content
├── simulator.html      # (Placeholder) Interactive Simulator
├── analyzer.html       # (Placeholder) AI Analyzer tool
└── README.md           # This file
🌐 Getting Started
Prerequisites
You only need a modern web browser (Chrome, Firefox, Edge, etc.) to view and interact with the site.

Installation
Since this is a purely frontend project, no installation steps are required.

Clone the repository (or download the files):

Bash

git clone https://github.com/UdayashankarAradhya/codefury-cyber-safety-project.git
Navigate to the project directory:

Bash

cd codefury-cyber-safety-project
Open index.html (or login.html) directly in your web browser.


🎨 Design Notes (For Developers)
The core aesthetic is controlled by a few key CSS features:

Variables: Defined in :root, allowing easy changes to colors, especially --accent and --accent-2.

Background: A complex radial-gradient and linear-gradient combination is used on body to create the deep space/dark backdrop.

Glassmorphism: Achieved via background: rgba(...) combined with backdrop-filter: blur(6px) on elements like .navbar and .hero-card.

Animated Blobs: Pure CSS animation (@keyframes floatY) and blurring (filter: blur(36px)) create the subtle, floating background elements.

🤝 Contribution
This project was created as part of the CodeFury 8.0 event. Contributions, suggestions, or bug reports are welcome.

© License
This line is important!
© 2025 Cyber Shield. A CodeFury 8.0 Project. (Please update or add a formal license like MIT if needed.)
