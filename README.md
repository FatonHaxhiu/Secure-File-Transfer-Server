# Secure File Transfer Server with SFTP

A Dockerized secure file transfer server using SFTP, integrated with Nginx for web access to uploaded files and Postfix for email notifications. Designed for secure, controlled file transfer environments, such as security testing or lab setups.

## ⚠️ Ethical Use Warning
This project is intended for **ethical and authorized use only** in controlled environments with explicit permission. Unauthorized use for malicious purposes, including phishing attacks, is strictly prohibited.

## Purpose
The Secure File Transfer Server provides a robust platform for secure file transfers, enabling:
- **Secure file uploads** via SFTP with SSH key-based authentication and a chroot jail for isolation.
- **Web access** to uploaded files through an Nginx server.
- **Email notifications** using Postfix for monitoring or alerting.
- Ideal for security professionals conducting authorized testing, such as simulating secure file transfer workflows or integrating into a phishing simulation framework (with permission).

## Features
- SFTP server with SSH key authentication and chroot jail for enhanced security.
- Nginx web server to serve uploaded files via HTTP.
- Postfix email server for sending notifications.
- Dockerized setup for easy deployment and portability.
- Scanned with Trivy to ensure no high/critical vulnerabilities in the base image.

## Prerequisites
- Docker and Docker Compose installed.
- WSL2 (Windows Subsystem for Linux) or a Linux environment for optimal performance.
- SMTP credentials for Postfix configuration (optional).
- GitHub account for repository management.

## Setup Instructions
1. **Clone the Repository**:
   
   git clone https://github.com/FatonHaxhiu/Secure-File-Transfer-Server.git
   cd Secure-File-Transfer-Server