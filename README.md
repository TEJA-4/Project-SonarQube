<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automated Code Quality Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1, h2, h3 {
            color: #333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li::before {
            content: "✔️ ";
            color: green;
        }
        code {
            background-color: #ddd;
            padding: 2px 5px;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <h1>🚀 Automated Code Quality Analysis with SonarQube, Jenkins & Docker</h1>
    <p>This project demonstrates <strong>automated code quality analysis</strong> using <strong>SonarQube</strong>, integrated with <strong>Jenkins, Docker, and DockerHub</strong>. The pipeline ensures <strong>secure, high-quality code</strong> by scanning for vulnerabilities, bugs, and security issues before deployment. 🚀</p>
    
    <h2>🎯 Project Overview</h2>
    <h3>🔹 Technologies Used</h3>
    <ul>
        <li><strong>SonarQube</strong> - Code quality & security analysis 🔍</li>
        <li><strong>Jenkins</strong> - Automating CI/CD pipelines ⚙️</li>
        <li><strong>Docker</strong> - Containerized environment for seamless execution 🐳</li>
        <li><strong>DockerHub</strong> - Storing & managing Docker images 📦</li>
    </ul>
    
    <h3>⚡ Workflow: End-to-End Process</h3>
    <ol>
        <li>Developer commits code to the repository 💻</li>
        <li>Jenkins triggers a build and fetches the latest code ⚙️</li>
        <li>SonarQube scans the code for security vulnerabilities 🛡️</li>
        <li>Docker builds an image with the analyzed application 🏗️</li>
        <li>Image is pushed to DockerHub for deployment 🚀</li>
    </ol>
    
    <h2>🔥 Setup & Installation Guide</h2>
    <h3>📌 Prerequisites</h3>
    <ul>
        <li>Install <strong>Jenkins, SonarQube, and Docker</strong> 🛠️</li>
        <li>Create an account on <strong>DockerHub</strong> 🌐</li>
        <li>Configure <strong>SonarQube in Jenkins</strong> for automated analysis 🔍</li>
    </ul>
    
    <h3>🛠️ Step-by-Step Setup</h3>
    <ol>
        <li>Install SonarQube & Jenkins in your environment 🖥️</li>
        <li>Configure SonarQube Scanner as a Jenkins tool 🔄</li>
        <li>Write a Jenkins Pipeline to analyze the source code 📝</li>
        <li>Build a Docker image with the validated application 🐳</li>
        <li>Push the Docker image to DockerHub for seamless deployment 🚀</li>
    </ol>
    
    <h2>⭐ Key Features & Benefits</h2>
    <ul>
        <li>🚀 <strong>Automated Code Scanning</strong> - Ensures high code quality with SonarQube 🔍</li>
        <li>🐳 <strong>Containerized Deployment</strong> - Runs inside Docker for portability 🏗️</li>
        <li>🔄 <strong>Continuous Integration</strong> - Automates builds & analysis with Jenkins ⚡</li>
        <li>🛡️ <strong>Secure Image Storage</strong> - Pushes validated images to DockerHub 🔒</li>
    </ul>
    
    <h2>🎯 Want to contribute?</h2>
    <p>Feel free to fork and submit a pull request! 💡</p>
</body>
</html>
