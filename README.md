# ET-VScanner

ET-VScanner is a command-line vulnerability scanner tool written in Python. It helps identify potential vulnerabilities in web applications by performing various scans and analysis.

## Features

- Initial scan: Performs an initial scan of the target URL to gather information about the web application.
- Vulnerability scans: Performs a series of vulnerability scans on the target URL using different modules.
- Directory enumeration: Scans for directories and files that may be exposed or accessible.
- Parameter injection: Scans for potential injection points in form parameters.
- Cross-Site Scripting (XSS): Searches for potential XSS vulnerabilities in JavaScript files.
- SQL injection: Searches for potential SQL injection points in the web application.
- Command injection: Searches for potential command injection points in the web application.
- Fetches vulnerability information: Fetches the latest vulnerability information from the National Vulnerability Database (NVD) or Common Vulnerabilities and Exposures (CVE) API.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/ET-VScanner.git
