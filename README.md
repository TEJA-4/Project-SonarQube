<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automated Code Quality Analysis</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; background-color: #f4f4f4; color: #333; padding: 20px; }
        h1, h2 { color: #007bff; }
        ul { list-style-type: none; }
        li::before { content: "✅ "; color: green; }
        .container { max-width: 800px; margin: auto; background: white; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
    </style>
</head>
<body>
    <div class="container">
        <h1>🌟 Automated Code Quality Analysis with SonarQube, Jenkins & Docker 🛠️</h1>
        <p>This project demonstrates automated code quality analysis using SonarQube, integrated with Jenkins, Docker, and DockerHub. The pipeline ensures secure, high-quality code by scanning for vulnerabilities, bugs, and security issues before deployment. 🚀</p>
        
        <h2>🎯 Project Overview</h2>
        <h3>🔹 Technologies Used 🛠️</h3>
        <ul>
            <li>SonarQube - Code quality & security analysis 🔍</li>
            <li>Jenkins - Automating CI/CD pipelines ⚙️</li>
            <li>Docker - Containerized environment for seamless execution 🐳</li>
            <li>DockerHub - Storing & managing Docker images 📦</li>
        </ul>
        
        <h2>⚡ Workflow: End-to-End Process 🔄</h2>
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
            <li>Install Jenkins, SonarQube, and Docker 🛠️</li>
            <li>Create an account on DockerHub 🌐</li>
            <li>Configure SonarQube in Jenkins for automated analysis 🔍</li>
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
            <li>🚀 Automated Code Scanning - Ensures high code quality with SonarQube 🔍</li>
            <li>🐳 Containerized Deployment - Runs inside Docker for portability 🏗️</li>
            <li>🔄 Continuous Integration - Automates builds & analysis with Jenkins ⚡</li>
            <li>🛡️ Secure Image Storage - Pushes validated images to DockerHub 🔒</li>
        </ul>
        
        <h2>🎯 Want to contribute? Feel free to fork and submit a pull request! 💡</h2>
    </div>
</body>
</html>
