# Catcher - Web Vulnerability Scanner

<p align="center">
  <pre>
  ______        __  ___________  ______    __    __    _______   _______   
 /" _  "\      /""\("     _   ")/" _  "\  /" |  | "\  /"     "| /"      \  
(: ( \___)    /    \)__/  \\__/(: ( \___)(:  (__)  :)(: ______)|:        | 
 \/ \        /' /\  \  \\_ /    \/ \      \/      \/  \/    |  |_____/   ) 
 //  \ _    //  __'  \ |.  |    //  \ _   //  __  \\  // ___)_  //      /  
(:   _) \  /   /  \\  \\:  |   (:   _) \ (:  (  )  :)(:      "||:  __   \  
 \_______)(___/    \___)\__|    \_______) \__|  |__/  \_______)|__|  \___)                                                                     
  </pre>
</p>


https://github.com/user-attachments/assets/fea24641-5dd2-48ba-8110-594312ac8d9a

Catcher is a  web vulnerability scanner designed to identify security vulnerabilities in web applications. It supports the detection of SQL injection, XSS, insecure file uploads, and many other vulnerabilities.

## Features

- **CMS Detection**: Detects popular CMS like WordPress, Joomla, Drupal, and Typo3.
- **File Upload Checks**: Checks for insecure file uploads and configuration files.
- **XSS Detection**: Detects Cross-Site Scripting (XSS) vulnerabilities.
- **SQL Injection**: Checks for SQL injection vulnerabilities.
- **Session Management**: Checks for session management vulnerabilities.
- **DOM Changes**: Analyzes insecure elements in the DOM.
- **Captcha Detection**: Detects missing captchas in forms.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/N3LL4-01/Catcher.git
    cd Catcher
    ```

2. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download Geckodriver:**
    Download [Geckodriver](https://github.com/mozilla/geckodriver/releases) and place it in the `website_scanner` directory.

4. **Set executable permissions for Geckodriver (macOS/Linux users only):**
    ```bash
    chmod +x path/to/geckodriver
    ```

## Usage

1. **Start the scanner:**
    ```bash
    python run.py
    ```

2. **Follow the prompts:**
    Enter the domain to scan (including `http://` or `https://`).

