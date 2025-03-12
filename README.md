# XSS-Scanner
A lightweight yet powerful security scanner for detecting XSS, HTML injection, and path traversal vulnerabilities. This tool automates vulnerability testing using a variety of payloads, analyzes responses, and generates a detailed report with a dark-themed UI. Perfect for security researchers and ethical hackers!

# XSS-Scanner

![XSS-Scanner]

A lightweight yet powerful security scanner for detecting **XSS**, **HTML Injection**, and **Path Traversal** vulnerabilities. This tool automates vulnerability testing using a variety of payloads, analyzes responses, and generates a **detailed HTML report** with a dark-themed UI. 🚀🔍

## Features
- ✅ **Automated XSS Testing** (Reflected, Stored, and DOM-based payloads)
- ✅ **HTML Injection Detection**
- ✅ **Path Traversal Exploitation**
- ✅ **Customizable Payload List**
- ✅ **Generates a Dark-Themed HTML Report** 📊
- ✅ **User-Agent Spoofing**

## Installation
### Prerequisites
- Python 3.x
- `requests` library
- `beautifulsoup4` library

### Install Dependencies
```sh
pip install requests beautifulsoup4
```

## Usage
Run the script with:
```sh
python scanner.py
```

The script will:
1. Test various **XSS**, **HTML Injection**, and **Path Traversal** payloads.
2. Analyze server responses.
3. Generate a **detailed HTML vulnerability report** if any vulnerabilities are found.

### Example Output
```
[✅] Potential vulnerability found with payload: <script>alert('1')</script>
[❌] Payload not reflected or evaluated: ../../../../etc/passwd
[✅] Vulnerability report generated: vulnerability_report.html
```

## Customization
You can modify the `payloads` list in `scanner.py` to add/remove payloads as needed.

## Disclaimer ⚠️
This tool is for **educational and ethical testing** purposes **only**. Unauthorized use against websites without explicit permission is illegal. Use responsibly!

## License
MIT License © 2025 XSS-Scanner-Pro Team
