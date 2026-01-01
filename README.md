# CodeAlpha_Secure-Coding-Review

This project demonstrates a secure coding review process on a Python-based Flask web application. The application includes a simple login functionality that is intentionally written with security flaws to simulate real-world vulnerable code.

## The goal of this project is to:

- Identify common security vulnerabilities through manual code review
- Understand how insecure coding practices can lead to attacks
- Recommend secure coding best practices
- Document findings and provide clear remediation steps
- Key Security Issues Identified
- SQL Injection vulnerability due to unsafe query construction 
- Debug mode enabled, which exposes sensitive information
- Plaintext password handling without hashing
- Tools & Techniques Used
- Manual secure code inspection
- Knowledge of OWASP Top 10 vulnerabilities
- Recommendation of static analysis tools (Bandit)

## Project Structure

secure_coding_review_project/
│
├── app.py               # Vulnerable Flask application
├── requirements.txt     # Project dependencies
└── SECURITY_REVIEW.md   # Security audit report & remediation

## Commands to Run the Project

 step 1: Extract the ZIP file
    
    unzip secure_coding_review_project.zip
    cd secure_coding_review_project

step 2:- Install required dependencies

    pip install -r requirements.txt

 If pip doesn’t work:

    python -m pip install -r requirements.txt

Step 3:- Run the Flask application
   
    python app.py

step 4:- Access the application

Open your browser and go to:

    http://127.0.0.1:5000

