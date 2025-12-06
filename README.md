# Moodle Docker Setup

This project provides a quick and easy way to set up and debug a Moodle environment using Docker and Docker Compose. 

## Version

- **Moodle Version**: 4.4.5

## Vulnerability Information

Please note that this setup is **vulnerable to CVE-2025-26529**.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Visual Studio Code (VS Code)](https://code.visualstudio.com/) (Recommended for development)
- [Container Tools (VS Code Extension)](Recommended for development)

## Getting Started
Follow these steps to get your PHP project running.

### 1. Clone the repository

Clone this repository to your local machine:

```bash
git clone <repository-url>
```


### Download the moodle source code 
```bash
wget <project download URL>
unzip <project download URL> 
mv project.zip src
```

```bash
chmod 777 src
```
```bash
docker-compose up -d
```


