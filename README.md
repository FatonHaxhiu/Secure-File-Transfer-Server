# Secure File Transfer Server with SFTP

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A Dockerized secure file transfer server using SFTP, integrated with Nginx for web access to uploaded files and Postfix for email notifications. Designed for secure, controlled file transfer environments, such as security testing or lab setups.

## ⚠️ Ethical Use Warning
This project is for **ethical and authorized use only** in controlled environments with explicit permission. Unauthorized use for malicious purposes, including phishing attacks, is strictly prohibited.

## Purpose
The Secure File Transfer Server enables secure file transfers for authorized testing scenarios, providing:
- **Secure SFTP uploads** with SSH key-based authentication and chroot jail isolation.
- **Web access** to uploaded files via Nginx.
- **Email notifications** through Postfix.
- Ideal for security professionals simulating secure file transfer workflows.

## Features
- SFTP server with 4096-bit RSA key authentication and chroot jail.
- Nginx server to serve uploaded files over HTTP.
- Postfix for email notifications.
- Dockerized for easy deployment.
- Scanned with Trivy for no high/critical vulnerabilities.
 
## Prerequisites
- Docker and Docker Compose
- WSL2 (Windows) or Linux environment
- SMTP credentials for Postfix (optional)
- GitHub account for cloning

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/FatonHaxhiu/Secure-File-Transfer-Server.git
   cd Secure-File-Transfer-Server

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.