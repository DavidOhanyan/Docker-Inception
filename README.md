# Inception

System Administration Project: Docker Infrastructure Setup

## Table of Contents:
- [Introduction](#introduction)
- [General Guidelines](#general-guidelines)
- [Mandatory Part](#mandatory-part)
- [Bonus Part](#bonus-part)

---

![Inception Logo](https://cestoliv.com/projects/imgs/42/inception.webp)

---

## Introduction

Welcome to my System Administration project where I've set up a Docker infrastructure to enhance my knowledge of system administration using Docker. This project focuses on virtualizing various Docker images, each serving a specific purpose, all orchestrated within a virtual machine environment.

## General Guidelines

- This project has been carried out within a virtual machine environment.
- All configuration files are organized within the `srcs` folder.
- A `Makefile` has been provided at the root of the directory to automate the setup process using `docker-compose.yml`.
- Extensive reading and documentation study on Docker usage have been undertaken to accomplish this assignment effectively.

## Mandatory Part

I've successfully implemented the following components as per the mandatory requirements:

- **NGINX Docker Container**: Configured to serve as the entry point into the infrastructure via port 443, supporting TLSv1.2 or TLSv1.3.
- **WordPress Docker Container**: Integrated with php-fpm and configured without nginx.
- **MariaDB Docker Container**: Set up as a dedicated database service.
- **Volumes**: Established volumes for WordPress database and website files.
- **Docker Network**: Established network connectivity between containers.
- **Automatic Restart**: Configured containers to restart in case of a crash.
- **Security Measures**: Avoided hacky patches and followed best practices for Dockerfile writing.
- **User Management**: Implemented user management within WordPress database, adhering to specified constraints.
- **Domain Configuration**: Configured domain name `login.42.fr` to point to the local IP address.

---

![diagram](https://github.com/DavidOhanyan/Docker-Inception/assets/117384850/5ea9ff64-c15c-4ff6-8abf-3b0c994023e0)

---

## Bonus Part

In addition to the mandatory requirements, I've accomplished the following bonus tasks:

- **Redis Cache for WordPress**: Implemented Redis cache for efficient cache management.
- **FTP Server Container**: Set up an FTP server container linked to the WordPress website volume.
- **Static Website**: Created a static website using a language other than PHP, serving as a showcase or resume site.
- **Adminer**: Configured Adminer for database management.
- **Additional Service**: Implemented an additional service tailored to specific needs, with justification provided.

---

Feel free to explore the project repository for detailed configuration files and Docker setups. If you have any questions or suggestions for improvement, don't hesitate to reach out. Thank you for reviewing my project! 🚀







