# PhishAlert - Phishing Site Detection

A Phishing Site Detection which also allows to safely view the website without actually visiting it. Built using Python. With PhishAlert, you can quickly identify suspicious websites and protect from phishing attacks. Techniques for phishing detection include analyzing URL patterns, checking for known malicious domains, employing machine learning models to detect suspicious website features. Effective phishing detection helps protect users from cyber threats and enhances online security.

## Features

These are the features provided by PhishAlert to its users.
- The website is easy to use, with a simple interface that anyone can navigate.
- Users can see the preview of the website without actually visiting it.
- PhishAlert gives a trust score to the URL, which will provide the user an understanding of the trustability and authenticity of the domain.
- PhishAlert provides crucial details (WHOIS, SSL and general) regarding the domain, which will help the user to get a basic understanding of the URL
- The URL is checked with a phish database (PhishTank) to see whether it is a reported phishing link.

## Project Structure

- **app.py**: Main application file that initiates the web app.
- **controller.py**: Handles the logic and operations of the application.
- **db.py**: Manages database interactions.
- **model.py**: Defines data models for the application.
- **onetimescript.py**: Script to be run once for initial setup or configurations.
- **instance/**: Contains instance-specific configurations or files.
- **static/**: Holds static assets such as CSS, JavaScript, and images.
- **templates/**: Contains HTML templates for rendering web pages.
- **vercel.json**: Configuration file for deploying on Vercel.
- **phishing.pptx**: A presentation explaining or demonstrating the project.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/username/Phishing-Site-Detection.git
    ```
    
2. **Run the Application**:
    ```bash
    python app.py
    ```

3. **Access the Application**:
    Open your browser and navigate to `http://localhost:5000`.

