# WebXploit-Scanner

WebXploit-Scanner is a powerful automation tool built in Python to assist Security Researchers in identifying critical vulnerabilities across large-scale URL lists. It focuses on high-impact flaws like XSS, RCE, SSRF, CRLF, SSTI, and SQL Injection error patterns.

## 🚀 Execution

Follow these steps to set up and run the tool:

```bash
# Navigate to the project directory
cd WebXploit-Scanner

# Run the scanner
python3 webxploit.py
```
<img width="740" height="250" alt="image" src="https://github.com/user-attachments/assets/edfec6a1-2683-41df-98a7-20c816cf6058" />

Note: WebXploit requires a .txt file containing target URLs. For best results, use tools like ParamSpider or Waybackurls to gather endpoints. Use the FUZZ notation in your URLs to specify exactly where you want payloads to be injected.

## ✨ Key Features

  •	Multi-Vulnerability Engine: Automated detection for XSS, RCE, SSRF, SSTI, and SQL Errors.

  •	Modular Scanning: Ability to skip specific vulnerability checks using command-line arguments to save time.

  •	Smart Fuzzing: Support for custom payload positioning via FUZZ notation.

  •	Collaborator Integration: Native support for Burp Suite Collaborator to detect Out-of-Band (OOB) RCE and SSRF.

# 🛠 Usage

  1.	Target Selection: Provide a text file containing the URLs you wish to analyze.
  2.	Payload Tuning: Choose parameter lengths and payloads based on the target environment's complexity.
<img width="740" height="250" alt="image" src="https://github.com/user-attachments/assets/c145570f-2e9a-4e6b-87b8-4fc3a0f8beab" />

## Burp Collaborator Integration
For reliable RCE and SSRF testing, using a Collaborator link is essential:

  •	Specify your unique Burp Collaborator client link when prompted.
  
  •	Press r to quickly reload and reuse a previous link during active sessions.

## 🤝 Contribution
Contributions and suggestions are highly valued! If you have ideas for new detection patterns or bug fixes, please open an issue or submit a pull request.

## ⚖️ License
This project is licensed under the Apache License 2.0.

## ⚠️ Disclaimer

This tool is intended for educational and ethical security testing purposes only. The developer is not responsible for any illegal use or damage caused by this tool. Always obtain proper authorization before testing any system.
