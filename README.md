💻 SynText — Interactive Coding & Authentication UI
A modern, responsive authentication screen for SynText featuring an animated multi-language code preview terminal.

🌟 Overview
SynText is designed to break down complex programming languages into step-by-step interactive lessons. This repository contains a sleek, production-ready login interface with a dual-pane layout:   
HTML

Left Panel (Hero & Code Visualizer): Features a dark theme editor with live typing animations cycling through multiple programming languages.   
HTML

Right Panel (Authentication Form): A clean, modern login form built with accessibility and smooth user interactions in mind.   
HTML

✨ Features
⚡ Animated Code Terminal: Simulates live typing effects across Python, Java, C++, C#, and CSS snippets.   
HTML

🎨 Modern Tech Stack Design: Built using Tailwind CSS and Plus Jakarta Sans typography.   
HTML

📱 Fully Responsive Layout: Seamlessly scales from mobile screens to desktop displays.   
HTML

👁️ Password Visibility Toggle: Dynamic password reveal functionality powered by plain JavaScript.   
HTML

🌐 Language Selector & SSO Options: UI elements for internationalization and third-party login providers (Google, GitHub, Apple).   
HTML

🚀 Zero Build Step: Runs directly in the browser using CDN references.   
HTML

🛠️ Built With
HTML5 & JavaScript (ES6+)

   
HTML

Tailwind CSS (via CDN)   
HTML

Google Fonts (Plus Jakarta Sans)   
HTML

🚀 Quick Start
Clone the repository:

Bash
git clone https://github.com/beekay12/syntext-login.git
Navigate into the directory:

Bash
cd syntext-login
Open the project:
Simply double-click index.html or open it using any browser of your choice.   
HTML

📂 Project Structure
Plaintext
.
└── index.html        # Main HTML layout, inline CSS, and typing animation script
⚙️ How It Works
The interactive code snippet box cycles through an array of code examples:

JavaScript
const snippets = [
    { file: 'main.py', code: 'print("Hello, Dev!")' },
    { file: 'Main.java', code: 'System.out.println("Hello World");' },
    { file: 'main.cpp', code: 'std::cout << "Build the future";' },
    { file: 'Program.cs', code: 'Console.WriteLine("Ready to code?");' },
    { file: 'styles.css', code: 'body { display: flex; }' }
];
The typeEffect() function controls character insertion, deletion speeds, and pause intervals to replicate a real developer typing inside an IDE window.   
HTML

📄 License
This project is open source and available under the MIT License.
