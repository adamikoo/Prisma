<div align="center">

<!-- Replace with your actual logo URL or local path like ./public/favicon.png -->

<img src="https://www.google.com/search?q=https://via.placeholder.com/150/2563eb/FFFFFF%3Ftext%3DLumina" alt="logo" width="100" height="auto" />

☁️ Lumina Notes

The intelligent, cloud-synced note-taking application built for the modern web.

<!-- Badges -->

<p>
<a href="https://reactjs.org/">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/React-20232A%3Fstyle%3Dfor-the-badge%26logo%3Dreact%26logoColor%3D61DAFB" alt="react"/>
</a>
<a href="https://vitejs.dev/">
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white" alt="vite"/>
</a>
<a href="https://tailwindcss.com/">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Tailwind_CSS-38B2AC%3Fstyle%3Dfor-the-badge%26logo%3Dtailwind-css%26logoColor%3Dwhite" alt="tailwind"/>
</a>
<a href="https://firebase.google.com/">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Firebase-FFCA28%3Fstyle%3Dfor-the-badge%26logo%3Dfirebase%26logoColor%3Dblack" alt="firebase"/>
</a>
<a href="https://deepmind.google/technologies/gemini/">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Google%2520Gemini-8E75B2%3Fstyle%3Dfor-the-badge%26logo%3Dgoogle%26logoColor%3Dwhite" alt="gemini"/>
</a>
</p>

<!-- Quick Links -->

<p>
<a href="https://www.google.com/search?q=https://lumina-notes.web.app">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/View_Demo-2563eb%3Fstyle%3Dflat%26logo%3Dgoogle-chrome%26logoColor%3Dwhite" alt="View Demo" />
</a>
<a href="https://www.google.com/search?q=https://github.com/adamikoo/Lumina/issues">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Report_Bug-d97706%3Fstyle%3Dflat%26logo%3Dgithub%26logoColor%3Dwhite" alt="Report Bug" />
</a>
<a href="https://www.google.com/search?q=https://github.com/adamikoo/Lumina/issues">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Request_Feature-10b981%3Fstyle%3Dflat%26logo%3Dgithub%26logoColor%3Dwhite" alt="Request Feature" />
</a>
</p>
</div>

<br />

<!-- Table of Contents -->

<details>
<summary>Table of Contents</summary>
<ol>
<li><a href="#-features">Features</a></li>
<li><a href="#-repository-structure">Repository Structure</a></li>
<li><a href="#-getting-started">Getting Started</a></li>
<li><a href="#-tech-stack">Tech Stack</a></li>
<li><a href="#-contributing">Contributing</a></li>
<li><a href="#-license">License</a></li>
</ol>
</details>

✨ Features

Lumina redefines the note-taking experience by combining a rich text editor with powerful AI tools and real-time collaboration.

Feature

Description

🧠 AI Intelligence

Powered by Google Gemini. Summarize notes, fix grammar, or let the AI auto-complete your sentences.

☁️ Cloud Sync

Built on Firestore. Notes update instantly across all devices in real-time.

🎨 Rich Media

Full WYSIWYG editor. Support for images (resize/move), sketching canvas, and voice-to-text.

🤝 Collaboration

Share notes via email. Assign Viewer or Editor roles for granular permission control.

🔐 Secure Auth

Complete authentication system supporting Google Sign-In, Email/Password, and Guest access.

📦 Power Tools

Import from Google Keep (.zip), export to .txt/Email, and full JSON backups.

📂 Repository Structure

└── Lumina/
    ├── public/
    │   ├── favicon.png
    │   └── manifest.json
    ├── src/
    │   ├── utils/
    │   │   └── keepImport.js
    │   ├── App.jsx
    │   ├── firebase.js
    │   ├── index.css
    │   └── main.jsx
    ├── .env
    ├── index.html
    ├── package.json
    ├── postcss.config.js
    ├── tailwind.config.js
    └── vite.config.js


🚀 Getting Started

Follow these steps to get a local copy up and running.

Prerequisites

Node.js (v16 or higher)

npm

A Firebase Project (Free tier is sufficient)

A Google AI Studio API Key

Installation

Clone the repository

git clone [https://github.com/adamikoo/Lumina.git](https://github.com/adamikoo/Lumina.git)
cd Lumina


Install dependencies

npm install


Configure Environment
Create a .env file in the root directory and add your keys:

VITE_GEMINI_API_KEY=your_google_gemini_api_key


Setup Firebase

Create a project at console.firebase.google.com.

Enable Authentication (Email, Google, Anonymous).

Enable Firestore Database.

Create src/firebase.js and paste your config object.

Start the App

npm run dev


📸 Screenshots

<div align="center">
<img src="https://www.google.com/search?q=https://via.placeholder.com/800x400%3Ftext%3DLumina%2BDashboard" alt="Dashboard" width="800" />







<img src="https://www.google.com/search?q=https://via.placeholder.com/800x400%3Ftext%3DDark%2BMode%2BEditor" alt="Editor" width="800" />
</div>

🛠 Tech Stack

Framework: React + Vite

Styling: Tailwind CSS

Icons: Lucide React

Backend: Firebase (Auth & Firestore)

AI Model: Google Gemini 1.5 Flash

Utilities: jszip (Imports), react-dom (Portals)

🤝 Contributing

Contributions make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License

Distributed under the MIT License. See LICENSE for more information.

<div align="center">

Created with ❤️ by Adamikoo

</div>
