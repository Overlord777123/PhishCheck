# 🛡️ PhishCheck | Threat Intelligence Engine

PhishCheck is a lightweight, client-side web application designed to inspect URLs for phishing indicators, malicious payloads, and social engineering tactics. 

Unlike traditional antivirus software, PhishCheck operates entirely in the browser. It uses a combination of heuristic analysis and signature-based matching to evaluate the risk level of a provided link without sending any data to external servers.

## ✨ Features

- **Deep Heuristic Analysis**: Detects typosquatting (using the Levenshtein distance algorithm), excessive subdomains, and suspicious URL structures.
- **Brand Impersonation Check**: Flags domains that attempt to spoof well-known brands (e.g., Google, PayPal, Sberbank).
- **Malicious Signature Database**: Matches URLs against a built-in blacklist of known phishing domains.
- **Payload Detection**: Identifies links pointing to dangerous executables (`.exe`, `.apk`, `.bat`) or double-extension attacks (e.g., `invoice.pdf.exe`).
- **Interactive Dashboard**: Displays a dynamic risk score (0-100) with an animated gauge and detailed terminal-style logs.
- **Export Reports**: Allows users to download a formatted `.txt` threat report for offline analysis.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure and layout.
- **CSS3**: Custom properties (variables), Flexbox/Grid layouts, keyframe animations, and responsive design.
- **Vanilla JavaScript (ES6+)**: URL parsing via the `URL` API, DOM manipulation, regular expressions (Regex), and the Levenshtein algorithm for string similarity.

## 🚀 How to Use

1. Clone this repository or download the source code.
2. Open the `index.html` file in any modern web browser.
3. Paste a suspicious URL into the input field and click **Deep Analyze**.
4. Review the risk score, detailed logs, and download the report if needed.

## ⚠️ Disclaimer

This project is for **educational purposes only**. The heuristic analysis is based on static URL structure and built-in signatures. It is not a substitute for professional cybersecurity solutions or real-time antivirus scanners. Always exercise caution when clicking unknown links.
