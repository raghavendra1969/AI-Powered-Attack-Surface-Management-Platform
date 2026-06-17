# AutoVAPT – Web & API Security Assessment Framework

## Overview

AutoVAPT is a Python-based Web and API Security Assessment Framework designed to assist security engineers and penetration testers in reconnaissance, endpoint discovery, authentication analysis, and vulnerability identification.

The framework automates common security assessment tasks and generates structured findings that help identify potential weaknesses in web applications and APIs.

## Features

### API Discovery & Inventory

* Automatic endpoint discovery
* API inventory generation
* Authentication status mapping
* OWASP API Security risk identification

### Authentication Analysis

* JWT token inspection
* Authentication flow analysis
* Authorization mapping
* Session security checks

### Reconnaissance

* Endpoint enumeration
* Response analysis
* Technology fingerprinting
* Route discovery

### Reporting

* Markdown report generation
* Structured findings
* Security observations
* Risk categorization

## Architecture

```text
Target Application
        │
        ▼
Reconnaissance Engine
        │
        ▼
Endpoint Discovery
        │
        ▼
Authentication Analysis
        │
        ▼
Security Checks
        │
        ▼
Report Generation
```

## Project Structure

```text
AutoVAPT/
├── modules/
├── findings/
├── reports/
├── screenshots/
├── main.py
├── requirements.txt
└── README.md
```

## Installation

```bash
git clone https://github.com/raghavendra1969/AutoVAPT.git
cd AutoVAPT

python -m venv venv

# Linux
source venv/bin/activate

# Windows
venv\Scripts\activate

pip install -r requirements.txt
```

## Usage

```bash
python main.py
```

Example:

```bash
python main.py --target https://example.com
```

## Sample Output

### API Inventory Report

```text
Total endpoints discovered: 4

GET  /api/users
POST /identity/api/auth/login
GET  /identity/api/v2/vehicle/vehicles
GET  /workshop/api/shop/products
```

## Security Focus Areas

* API Security
* Authentication Testing
* Authorization Review
* OWASP API Security Top 10
* Web Application Security

## Future Enhancements

* Automated JWT Security Testing
* Broken Access Control Detection
* API Fuzzing Engine
* Severity Scoring System
* Interactive Dashboard
* CI/CD Security Integration

## Disclaimer

This project is intended for educational purposes and authorized security testing only. Users are responsible for ensuring they have proper authorization before scanning or testing any system.

## Author

Raghavendra S.

Computer Science Engineer | Security Engineering Enthusiast | Application Security & Product Security
