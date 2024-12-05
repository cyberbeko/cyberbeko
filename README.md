<h1>Hey, I'm Berkay! <br/><a href="https://github.com/cyberbeko">Junior SOC Analyst</a>, <a href="https://www.linkedin.com/in/berkayyildirim44/">Cybersecurity Threat Analysis</a>, <a href="https://www.youtube.com/@BerkayYildirim-BY">YouTuber</a></h1>
## SQL-Injection-XSS-Protection-WAF 🛡️
A simple, educational Web Application Firewall (WAF) built with Flask, designed to block common web vulnerabilities such as SQL Injection and Cross-Site Scripting (XSS) attacks. This project serves as a foundational example of how to secure a Flask-based web application by filtering malicious input in HTTP requests (GET and POST). It is intended for learning purposes and should not be used in production environments without further security measures.

<h2>🧑🏻‍💻My Cybersecurity Projects:</h2>
<h1>Berkays_WAF🧑🏻‍💻</h1>

- <b>Bash</b>
  - [Secure DiskWipe: External Drive Data Erasure](https://github.com/cyberbeko/disk_sanitization.git)
- <b>Python</b>
  - [Package Delivery Application (Datastructures and Algorithms Demo)]()
 ### [YouTube Demonstration](https://www.youtube.com/@BerkayYildirim-BY)

<h2>📄Certifications</h2>
<h2>Description</h2>
The main goal of this project is to provide a basic Web Application Firewall (WAF) using Flask to help block common attacks such as SQL Injection and Cross-Site Scripting (XSS). This simple WAF serves as an introductory example for developers who want to understand how WAFs function and how they can be implemented in a web application. The project demonstrates how to inspect HTTP requests for malicious patterns and return a 403 Forbidden response when suspicious activity is detected.

- [Google Cybersecurity Program](https://i.imgur.com/QxSc2VB.png)
- [HIPAA](https://i.imgur.com/KVFDQj2.png)
## Programming Language💻
- **Python** (The primary language used for this project.The WAF is built using Flask, which is a web framework for Python.)

<h2>🎥 My YouTube Videos</h2>
## Utilities Used 💼
- **flask**: A lightweight web framework for Python, used to build the web application and the Web Application Firewall (WAF). Used for routing, handling HTTP requests, and building a simple web application.

- [Cybersecurity Starting From Zero 2025](https://youtu.be/3Br7dL2BIbE?si=07l3-KORnNeuhbgd)
- [Daily Life](https://youtu.be/lgzWLmlhG2Y?si=JjVgxScQY1-nOCjx)
- **Flask Middleware**: The custom middleware built into the Flask app to intercept and filter incoming HTTP requests (both GET and POST), blocking patterns associated with SQL Injection and XSS attacks.

<h2> 🖐🏻 Connect with me</h2>
- **Python Standard Libraries**:
jsonify: A Flask utility to return JSON responses, which is used to send the "Blocked by WAF" message.
request: A Flask object used to access incoming HTTP request data (query strings, body data).

<h2>Environments Used </h2>

- <b>**macOS**</b>

<h2>Program walk-through🦺</h2>

<p align="center">
Created waf_project folder <br/>
<img src="https://i.imgur.com/CMwnZVB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a Python file named Berkays_WAF.py  <br/>
<img src="https://i.imgur.com/FfuXL2L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Write the Flask WAF Code <br/>
<img src="https://i.imgur.com/iOHMmwR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Save and Exit
To save the file in nano and exit.
<br />
<br />
Install Flask and Run the Flask App:  <br/>
<img src="https://i.imgur.com/m9kHRQS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now we are ready to check!  <br/>
<img src="https://i.imgur.com/ofz9zdQ.png?1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Let's test the SQL Injection, try visiting this URL in browser:
<br/>
<img src="https://i.imgur.com/JtR0rpO.png?1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> As you see, The WAF should detect the malicious pattern.
<br /> Return a 403 Forbidden response with the following message.
<br /> Also, when I try with Cross-Site Scripting(XSS) it will say blocked by WAF <br/>
<br />
<br />
  
# CyberBeko WAF (Web Application Firewall)

## Summary

1. **Step 1:** Create a new folder and Python file (`Berkays_WAF.py`).
2. **Step 2:** Paste the WAF code to inspect query strings and POST data for SQL Injection and XSS patterns.
3. **Step 3:** Install Flask using `pip3 install flask`.
4. **Step 4:** Run the Flask app using `python3 Berkays_WAF.py`.
5. **Step 5:** Test the WAF by visiting your local server and attempting SQL Injection or XSS.

## Purpose:
To demonstrate the basic concepts of a Web Application Firewall (WAF) using Flask, specifically to prevent SQL Injection and XSS attacks.

## Goal:
1. **Educational Tool:** Teach developers about WAFs and basic web security.  
2. **Security Awareness:** Raise awareness about the importance of web application security.  
3. **Foundation for Growth:** Provide a starting point for more advanced security features.  
4. **Promote Best Practices:** Encourage basic security practices and proper web app protection.

## Disclaimer

### Important Note:

- This project is intended for **educational purposes only** and should not be used in **production environments**. It is a simple example to demonstrate the basic concepts of a Web Application Firewall.
  
- For real-world applications, it is crucial to use a more **robust and production-ready WAF solution**, such as **ModSecurity** or other advanced security tools.
  
- This basic WAF does not cover all possible attack vectors and should not be relied upon for securing sensitive or high-traffic applications.
  
- Always consider **additional layers of security**, such as input validation, content security policies (CSP), HTTPS, and other security best practices when developing web applications.
  
- In **production environments**, be sure to use a proper **WSGI server** like **Gunicorn** or **uWSGI** to run Flask apps securely and efficiently.

<a href="https://www.youtube.com/@BerkayYildirim-BY" target="_blank">
  <img src="https://i.imgur.com/npm9IOb.png" width="22px" alt="YouTube logo">
</a>

<a href="https://www.linkedin.com/in/berkayyildirim44/" target="_blank">
    <img src="https://i.imgur.com/AmJua6b.png" width="22px" alt="LinkedIn logo">
  </a>
  <a href="https://x.com/berkayildirimx" target="_blank">
    <img src="https://i.imgur.com/a1V38f9.png" width="22px" alt="Twitter logo">
  </a>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
