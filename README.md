# Christopher Harrison - Personal Website

A professional single-page personal website showcasing my experience, built with Node.js and deployed on Railway.

## Overview

This project serves as my digital portfolio, featuring:

- **LinkedIn & GitHub Integration**
- **Experience Timeline** detailing my work at Woodward, Thermo Fisher, and others.
- **Core Competencies** & **Education** sections.

## Tech Stack

- **Backend:** Node.js (Express) - Serving static files.
- **Frontend:** HTML5, CSS3 (Modern Dark Theme with Glassmorphism).
- **Deployment:** Railway (via Railpack).

## Local Development

To run this project locally:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/ChrisUFO/charrison.us.git
    cd charrison.us
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Start the server:**

    ```bash
    npm start
    ```

4.  **View the site:**
    Open `http://localhost:3000` in your browser.

## Deployment

This project is configured for **Railway** deployment using **Railpack**.

- **Zero Config:** No `Dockerfile` is required. Railpack automatically detects the Node.js application and builds it.
- **Environment:** The `start` script in `package.json` (`node index.js`) is automatically detected and used to run the application.

## Structure

```
.
├── public/                 # Static assets
│   ├── index.html          # Main HTML structure
│   ├── style.css           # Styling
│   ├── headshot.png        # Profile image
│   └── Chris_Harrison_Resume.docx
├── index.js                # Express server entry point
├── package.json            # Dependencies and scripts
└── README.md               # Project documentation
```
