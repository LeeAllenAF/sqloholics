/Users/carewell/Code/sql-trainer/README.md
# SQLoholics
_(pronounced es-que-oliks)_

[![GitHub license](https://img.shields.io/github/license/AlienFishConsulting/sqloholics.svg)](https://github.com/AlienFishConsulting/sqloholics/blob/main/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/AlienFishConsulting/sqloholics.svg)](https://github.com/AlienFishConsulting/sqloholics/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/AlienFishConsulting/sqloholics.svg)](https://github.com/AlienFishConsulting/sqloholics/issues)

---
![SQLoholics Logo](public/logo.png)

Welcome to **SQLOholics** – the fun, engaging, and supportive way to learn SQL from scratch!
Our application combines humor with education to make your SQL learning journey enjoyable and effective.

---

## Table of Contents

[Features](#features)

[Getting Started](#getting-started)

[Installation](##Installation)

[Usage](#usage)

[Contributing](#contributing)

[License](#license)

[Contact](#contact)

---

## Features (Coming Soon)

Interactive Lessons: Step-by-step tutorials to teach you SQL from the basics to advanced topics.

Practical Exercises: Hands-on practice with real-world SQL queries and problems.

Community Support: Connect with other learners who share your journey and goals.

Humor and Fun: Learn in a light-hearted environment with plenty of SQL-related puns and jokes.

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

## Prerequisites
Before you start, make sure you have the following software installed on your machine:

- Docker
- DBeaver

### Download and Install Docker

#### Windows

1. Download Docker Desktop for Windows from the [official Docker website](https://www.docker.com/products/docker-desktop).
2. Run the installer and follow the on-screen instructions to complete the installation.
3. After installation, launch Docker Desktop and ensure it is running.

#### macOS

1. Download Docker Desktop for Mac from the [official Docker website](https://www.docker.com/products/docker-desktop).
2. Open the downloaded `.dmg` file and drag the Docker icon to the Applications folder.
3. Launch Docker from the Applications folder and follow the on-screen instructions.

### Download and Install DBeaver

#### Windows

1. Download DBeaver Community Edition for Windows from the [official DBeaver website](https://dbeaver.io/download/).
2. Run the installer and follow the on-screen instructions to complete the installation.

#### macOS

1. Download DBeaver Community Edition for macOS from the [official DBeaver website](https://dbeaver.io/download/).
2. Open the downloaded `.dmg` file and drag the DBeaver icon to the Applications folder.
3. Launch DBeaver from the Applications folder.

### Download and Install Node.js

#### Windows

1. Download the Node.js installer for Windows from the [official Node.js website](https://nodejs.org/).
2. Run the installer and follow the on-screen instructions to complete the installation.

#### macOS

1. Download the Node.js installer for macOS from the [official Node.js website](https://nodejs.org/).
2. Open the downloaded `.pkg` file and follow the on-screen instructions to complete the installation.

## Running the Docker Compose File

1. Open a terminal or command prompt.
2. Navigate to the directory where the `docker-compose.yaml` file is located.
3. Run the following command to start the MySQL container:

```sh
   docker-compose up -d
```

## Connecting to the Database Using DBeaver
1. Launch DBeaver.
2. Click on the Database menu and select New Database Connection.
3. In the Connect to a database wizard, select MySQL and click Next.
4. Enter the following connection details:
   - Host: localhost
   - Port: 3306
   - Database: sqloholics_intro
   - Username: bill
   - Password: wilson
5. Click on the Test Connection button to ensure the connection is successful.
6. If the test is successful, click Finish to save the connection.
   
You are now connected to the MySQL database and can start working with it using DBeaver!

---


## Contributing
We welcome contributions from the community! If you'd like to contribute, please fork the repository and create a pull
request with your changes. Make sure to follow the project's code style and include tests for any new features or bug fixes.

```shell
# Create a new branch for your feature or bugfix:
git checkout -b feature-name

# Commit your changes:
git commit -m "Add new feature"

# Push to the branch:
git push origin feature-name
```

## License
This project is licensed under the MIT License. See the LICENSE file for more information.

## Contact
If you have any questions or need further assistance, feel free to reach out to us:


**Author**: Lee Allen

**Email**: [lee@alienfishconsulting.com](mailto:lee@alienfishconsulting.com)

**GitHub** [AlienFishConsulting](https://github.com/AlienFishConsulting)

